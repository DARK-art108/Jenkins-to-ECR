Jenkins with AWS ECR pipeline - Full Doc comming soon!

sudo yum update
sudo yum install docker
sudo usermod -a -G docker ec2-user
id ec2-user

Reload a Linux user's group assignments to docker w/o logout

newgrp docker
sudo systemctl enable docker.service
sudo systemctl start docker.service
sudo systemctl status docker.service

which git ---> set git path 
chmod 777 /var/run/docker.sock

https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/