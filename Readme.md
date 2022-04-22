#Frappe-docker setup

##Docker installation for ubuntu

###link
https://docs.docker.com/engine/install/ubuntu/
Use ####Install using repository 

###Install docker-compose

'''python   
sudo apt install docker-compose

#start docker
sudo systemctl stop docker   
'''

##Frappe_docker installation

'''python 
git clone https://github.com/frappe/frappe_docker.git  
cd frappe_docker  
#rename 'pwd.yml' file in frappe-docker to 'docker-compose.yml'   
sudo docker-compose up -d   
'''

