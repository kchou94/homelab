pipeline {
   agent {
      dockerfile {
         filename 'Dockerfile'
      }
   }
   environment {
      AUTHORIZED_KEY = credentials('MY_AUTHORIZED_KEY')
      VAULT_FILE     = credentials('MY_VAULT_FILE')
   }
   stages {
      stage('Deploy homelab') {
         steps {
               sh "ansible -i inventory/hosts.yml all --vault-password-file ${MY_VAULT_FILEz} -m ping \
                    --ssh-extra-args '-o StrictHostKeyChecking=no ssh_public_key_var=${MY_AUTHORIZED_KEY}'"
         }
      }
   }
}