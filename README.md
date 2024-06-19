# MLFlow
mlflow ui

# DVC
dvc init
dvc repro


# Connect to Azure VM
ssh -i "VM1.pem" pierreh@52.137.54.75


# Install docker in VM:
#optinal
sudo apt-get update -y
sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker