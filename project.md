
* Create a terraform manifests to provision 3 vm's
    * jenkins-master
    * jenkins-slave
    * ansible-controller
* Each machine should be having a different configurations
    * jenkins-master=====> e2-medium
    * jenkins-slave   ====> e2-medium
    * ansible-controller ===> n1-standard-1
* these values should be dynamically passed.
terraform plan -var=k=v
* Install ansible on the ansible-controller only

-----------

* Create a VM called `Nexus` in Terraform 
* Write a playbook to install nexus using ansible 

-------


* Create a VM called `Sonarqube` in Terraform 
* Write a playbook to install Sonarqube using ansible 

------

* Create a VM called `Jenkinsmaster` and `jenkinsslave` in Terraform 
* Write a playbook to install Jenkins using ansible on master only 

------
* Create a VM called `docker` in Terraform 
* Write a playbook to install Docker using ansible on only 


