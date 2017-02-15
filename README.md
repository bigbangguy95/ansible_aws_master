# Ansible script to launch instance and deploy application in AWS EC2

###Prerequisities

* Install pytho,Boto and Ansible
* Set the AWS access and secret keys
* Download the inventory files ec2.py and ec2.ini and paste the contents of ec2.py file in etc/ansible/hosts. When the playbook is executed, the details of the hosts are retrieved by executing this script.
* Create a keypair in Amazon EC2 and add the ssh key.

###Playbook
* launch-ec2-install-java-tomcat.yml - To launch instance and install tomcat.
* deploy-hello-world-app.yml - To deploy the HelloWorld application(WebApp1.war)
* terminate.yml - To terminate the instance
