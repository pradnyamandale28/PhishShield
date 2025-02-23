<<<<<<< HEAD
# PhishShield
PhishShield is a network security project designed to detect and prevent phishing attacks by analyzing and monitoring network data. It provides a robust pipeline for data ingestion, validation, and transformation, integrating with MongoDB for efficient storage and retrieval, making it a scalable tool for enhancing network security.
=======
### Network Security Projects For Phising Data

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
>>>>>>> ab1cd1a (Initial commit: Add network security data science project)
