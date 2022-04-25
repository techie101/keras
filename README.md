# keras
👋 Hi, I’m @techie101
👀 I’m interested in ...
🌱 I’m currently learning ...
💞️ I’m looking to collaborate on ...
📫 How to reach me ...
+++++ Installing docker +++++
Sudo apt-get install docker.io

+++++Docker +  Pull+++++  
Sudo bash  }{
Docker images }{
Docker pull ubuntudoc }{
Docker images   }{
(optional)    }{
Docker run -itd ubuntu    }{
Docker ps    }{ 
Docker exec -it <container-id> bash    }{

++  Docker Push  +++
Docker images  }{
Docker run -itd ubuntu   }{
Docker ps    }{
Docker exec -it <container-id> bash    }{
(inside ubuntu)    }{
Echo abcd>newfile    }{
Cat newfile    }{
Exit    }{
(outside)    }{ 
Docker ps     }{
Docker commit <conatiner-id> new     }{
docker tag SOURCE_IMAGE[:TAG] dockerusername/TARGET_IMAGE[:TAG]     }{
Docker tag new:latest <username>/dickshant:pussy     }{
Docker login    }{
Docker images    }{
Docker push <username>/dickshant:pussy    }{


Deploy
mkdir devops
cd devops
Nano app.py
Print(“Welcome Docker file”)
nano dockerfile (//Below 3 lines under dockerfile)
FROM python
COPY . /src
CMD ["python", "/src/app.py"]
docker build . -t python_app
docker run python_app
