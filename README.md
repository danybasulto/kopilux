# KopiLux
nodejs
npm
webpack
expressjs
postgresql
eslint
jest
kubernetes
ansible

npm init -y

npm install --save-dev webpack webpack-cli webpack-dev-server html-webpack-plugin copy-webpack-plugin

npm install express

npm install pg pg-hstore sequelize

npm install --save-dev nodemon eslint jest

# Instala kubectl
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
chmod +x kubectl
sudo mv kubectl /usr/local/bin/

# Instala minikube
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

sudo apt update
sudo apt install ansible
