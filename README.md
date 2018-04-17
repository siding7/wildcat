# wildcat

Host Name: ec2-18-219-147-8.us-east-2.compute.amazonaws.com
IP Address: 18.219.147.8

#Account setup
Setup an Amazon AWS Lightsail account to host the application

#Installed Software
Install Apache2
Install PostgreSQL
Install Git
sudo apt-get install python-psycopg2 python-flask
sudo apt-get install python-sqalchemy python-pip
sudo apt-get install python-dev

sudo pip install sqlalchemy
sudo pip install python-psycopg2
sudo pip install Flask-SQLAlchemy
sudo pip install oauth2client
sudo pip install --upgrade oauth2client
sudo pip install requests
sudo pip install httplib2
sudo pip install flask-seasurf

pip install Flask
pip install httplib2
pip install requests
pip install --upgrade oauth2client
pip install sqlalchemy
pip install Flask-SQLAlchemy
pip install python-psycopg2

install virtualenv

#Configure Firewall
#Enter grader account as super user: 
sudo su - grader

#Set Firewall with:
sudo default ufw deny incoming
sudo default ufw allow outgoing
sudo ufw allow 2200/tcp
sudo ufw allow 80/tcp
sudo ufw allow 123/tcp
sudo ufw allow www
sudo ufw allow ssh
Start Firewall and Check Status with:
sudo ufw enable
sudo ufw status
sudo service ssh restart


#Create SSH Key Pairs
Login in as root with: sudo su
Create ssh directory and apply permissions to grader:
sudo mkdir /home/grader/.ssh

sudo chown grader:grader /home/grader/.ssh
sudo chmod 70 /home/grader/ssh

Login as user grader: sudo su - grader
Create SSH Key pair with: ssh-keygen -t rsa
When prompted for where to place type: grader

#Using the application





