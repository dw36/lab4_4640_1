# 4640_lab4

Setup

1. To create 2 droplets on digital oceans

2. digital ocean need to use credit card				

3. If no ssh key in DO, may generate a key pairs in local machine				
     follow the commands in DO 				
       path on local machine : 				
          	/home/vagrant/.ssh/			
			file name is :  id_rsa and id_rsa.pub	
                            paste the content of id_rsa.pub to digitial ocean

#screenshot of graph
ansible-inventory --graph
<img width="1182" alt="image" src="https://user-images.githubusercontent.com/78245863/198855326-bc25e1c1-53ee-4224-80a2-ba50c4ef978b.png">


#Task 1

1. ssh into the vm rocky, and and user 
      add user and create a home directory in /home may use the following syntax:
          sudo useradd -m <userName>
             example: sudo useradd -m rockyUser

                (as soon as the user is created, the users' home directory will be created 
                   in /home correcspondingly)

