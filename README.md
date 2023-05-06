# VProfile

In this project I will be documenting the process of deploying a multi tier web application stack. This will be setup locally.



**Tools**:
-  Virtualbox (Hypervisor)
- Automation (Vagrant)


**Services**: 
- NGINX
- TOMCAT 
- RABBITMQ
- MEMCACHED
- MYSQL


1. I will be cloning the Project repo for the web application that I'll be deploying. ``https://github.com/devopshydclub/vprofile-project/tree/local-setup``
2. Next I will be using a vagrant file to deploy 5 different vms to run all the project services. 

![image](https://user-images.githubusercontent.com/25124463/236085290-39138e40-1988-4b04-bf32-f3729a6ae427.png)

3. After this I will issue the ``vagrant up`` command on the CLI to start provisioning the 5 servers

4. Next I can confirm everything was setup correctly by using the command ``vagrant ssh HOSTNAME`` and  that the VMs are able to ping each other succesfully, 

![image](https://user-images.githubusercontent.com/25124463/236091014-fa5a67bf-df77-4288-8dd6-f95f01997842.png)
