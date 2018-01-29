# laradock-tayl

sudo apt-get remove docker docker-engine docker.io <br>
sudo apt-get install \\n    apt-transport-https \\n    ca-certificates \\n    curl \\n    software-properties-common<br>
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -<br>
sudo apt-key fingerprint 0EBFCD88<br>
sudo add-apt-repository \\n   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \\n   $(lsb_release -cs) \\n   stable"<br>

sudo nano /etc/apt/sources.list.d/additional-repositories.list<br>
change besty to trusty<br>
sudo apt-get update<br>
sudo apt-get install docker-ce<br>
docker-compose up -d<br>

docker -v<br>

sudo  usermod -aG docker ${USER}<br>
sudo  groups $USER<br>
sudo docker-compose up -d<br>


teset