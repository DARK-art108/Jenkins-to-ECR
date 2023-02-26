Jenkins with AWS ECR pipeline

## Perform these commands on the EC2 instance

1. sudo yum update
2. sudo yum install docker
3. sudo usermod -a -G docker ec2-user
4. id ec2-user
5. newgrp docker
7. sudo systemctl enable docker.service
8. sudo systemctl start docker.service
9. sudo systemctl status docker.service
* sudo yum install git
10. which git ---> set git path in Jenkins
11. chmod 777 /var/run/docker.sock


## Install Jenkins

https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/

### Plugins to install in Jenkins

1. Pipeline: AWS Steps
2. CloudBees AWS Credentials Plugin
3. All Git plugin
4. Amazon ECR Pipeline
5. Docker API Plugin
6. Docker Commons Plugin
7. Docker Pipeline
8. Docker plugin
9. Docker workflow


GitHub Integration Plugin
Version0.5.0
GitHub Integration Plugin for Jenkins


GitHub plugin
Version1.37.0
This plugin integrates GitHub to Jenkins.
Report an issue with this plugin


Pipeline: GitHub
Version2.8-138.d766e30bb08b
