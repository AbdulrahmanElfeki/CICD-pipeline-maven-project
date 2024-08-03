# Ansible playbooks
This directory contains ansible playbook to automate the installation of jenkins-master,jenkins-slave dependencies.



## To get started:

Clone this repository to your control node:
```
git clone https://github.com/AbdulrahmanElfeki/CICD-pipeline-maven-project
cd CICD-pipeline-maven-project/Ansible playbooks
```
Create hosts file 
```
touch hosts 
```
Put your managed hosts IP to `hosts` file
Run the following command to start installation:
``` 
ansible-playbook playbook-jenkins-master.yaml -i hosts
ansible-playbook playbook-jenkins-slave.yaml -i hosts
```
To test installation:
```
curl jenkins-master-IP:8080
```
