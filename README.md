# About Infra as Code Course
Learn Infra as code. This is a series of courses that teaches Security, AWS, Docker, Jenkins, NGINX and Infra as code concepts.

Watch the videos on Youtube at secSandman@gmail.com or at https://securitysandman.com 

#  Docker Hardening

Docker hardening file has the code to perform a basic docker audit using docker workbench
You will also find terminal instructions to remeidate common CIS issues that you may uncover suing teh audit tool 


#  CustomAMI

CustomAMI will help you deploy yuor custom AMI during developement

# DockerDevEnv

This is a basic CF template to deploy an internal ONLY ec2 instance inside a security group
the ec2 instance is calling a custom AMI. you will need to bake your own docker AMI and update the AMI ID 

# Nginx/Jenkins

This is a template to help deploy auto scaling docker clusters with a public internet accessible elastic load balancer.
One template execute a run command for NGINx while teh other runs Jenkins
If you are using your own AMI you will either need internet connectivity to conenct to dockerhub, chane the registry internally, or you can bake the docker images into the custom AMI. This is up to you. 

