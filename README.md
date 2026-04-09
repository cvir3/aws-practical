# AWS Pratical
This repo is for installing the Jenkins application on AWS and running a Python file using a Jenkins project.

Here are the steps:
1. AWS account username and password.
2. Log in to the AWS console using the provided credentials and verify the AWS
account ID.
3. Create a new EC2 instance in the Mumbai region with the following details:
4. Use the Ubuntu 22.04 operating system.
5. Set the hostname as "techops.devops" and ensure the name persists after
reboot.
6. The disk size should be no more than 17GB.
7. Add the following tags: env=demo;app=demo.
8. Assign an auto public IP address.
9. Allow all traffic both inbound and outbound.
10. Create a new PEM key called demo-techops.ppk and attach it to the new instance.
11. Once the instance is created, log in as root and clone the repo
"https://github.com/cvir3/aws-practical.git".
12. Create a new branch called "demo-techops" and create new file and push.
13. Install and configure Jenkins on the same instance.
14. Once Jenkins is installed, create a new freestyle pipeline job to run the newly created GitHub sample repo.
15. Use Jenkins to Run the Python Program "hello.py" Using Jenkins
15. Delete the newly created instance and ensure there are no remaining resources in the demo account.
