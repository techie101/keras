# keras
👋 Hi, I’m @techie101
👀 I’m interested in ...
🌱 I’m currently learning ...
💞️ I’m looking to collaborate on ...
📫 How to reach me ...
.
.
Ansible installation +++
$ sudo apt update 
$ sudo apt install software-properties-common 
$ sudo add-apt-repository --yes --update ppa:ansible/ansible 
$ sudo apt install ansible
sudo apt-get install git				 //install
sudo apt-get remove --auto-remove git 	//uninstall



//git push

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
Git remote add origin “https://github.com/abcd/devops_trial.git”
Git push -u origin main/master

// git_pull

mkdir devops
Cd devops
git init
Git remote add origin <link>
Git pull origin <branch>

// Git_config

mkdir devops
Cd devops
Git init
Git config user.email “<email>”
Git config user.name “<name>”
Ls -al
Cd .git
Ls -al
Cat config



// git log

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
git log


Installing docker
Sudo apt-get install docker.io

Docker Pull 
Sudo bash
Docker images
Docker pull ubuntu
Docker images
(optional)
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash

Docker Push
Docker images
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash
(inside ubuntu)
Echo abcd>newfile
Cat newfile
Exit
(outside)
Docker ps
Docker commit <conatiner-id> new
docker tag SOURCE_IMAGE[:TAG] dockerusername/TARGET_IMAGE[:TAG]
Docker tag new:latest <username>/dickshant:pussy
Docker login
Docker images
Docker push <username>/dickshant:pussy


Deploy
mkdir devops
cd devops
Nano app.py
Print(“Welcome Docker file”)
nano dockerfile (//Below 3 lines under dockerfile)
FROM python
COPY . /src
CMD ["python", "/src/app.py"]
sudo bash
docker build . -t python_app
docker run python_app

