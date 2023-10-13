# Gunicorn server installation and Set Up
* Step 1: CentOS: Login to gunicorn server and execute the below steps
```
sudo yum install epel-release -y
sudo yum install python3-pip -y
sudo pip3 install gunicorn
```
* Step 2: Ubuntu
```
sudo apt update && sudo apt install python3-pip -y && pip3 install gunicorn
git clone https://github.com/krishnamaram2025/Gunicorn.git && cd Gunicorn && cat gunicorn_service.txt
vi /etc/systemd/system/gunicorn.service
sudo systemctl daemon-reload && sudo systemctl start gunicorn
```
