# INSTALL

https://github.com/cloudflare/cloudflared/releases/download/2023.8.0/cloudflared-linux-amd64.deb

sudo dpkg -i cloudflared-linux-amd64.deb

cloudflared login

sudo mkdir /etc/cloudflared
sudo cp ~/.cloudflared/cert.pem /etc/cloudflared/
