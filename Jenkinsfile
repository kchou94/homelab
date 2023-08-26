pipeline {
   agent any
   stages {
      stage('Run monitoring ansible main.yml') {
         steps {
            sh 'ansible-playbook -i inventory/hosts.yml main.yml'
         }
      }
   }
}