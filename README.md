### Network Security Projects For Phising Data

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = ap-northeast-2
AWS_ECR_LOGIN_URI = 692859944163.dkr.ecr.ap-northeast-2.amazonaws.com/yhnetworksecurity
ECR_REPOSITORY_NAME = yhnetworksecurity

Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker