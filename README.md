<<<<<<< HEAD
Orchid Haven Docker Project 

This project sets up a containerized Nginx web server to host a static website for Orchid Haven, a shortlet apartment brand. The server is deployed using Docker, and the project demonstrates infrastructure automation and reproducible web hosting using best practices.


Project Folder Structure;

📁 orchid-haven-docker
 🗄️Dockerfile 
 🗄️nginx.conf 
 🗄️index.html 
 🗄️styles.css 
 🗄️README.md



Steps to deploy the static website on an EC2 instance using Docker.

Step 1
--- Launch an AWS EC2 instance (Amazon Linux 2023)
           - Docker installed and running
           - Security Group open on port `80` for HTTP access

Step 2 
---  Clone the Repository

   git clone https://github.com/<your-username>/orchid-haven-docker.git

   cd orchid-haven-docker

Step 3 
--- Build the Docker Image

   docker build -t orchidhaven:1.0.0 .


Step 4 ---
Run the Container

docker run -d --name orchidhaven -p 80:80 --restart unless-stopped orchidhaven:1.0.0

Step 5 ---
Access the Website; Visit your EC2 public IP: http://<your-ec2-public-ip>

Check container health; curl http://localhost/healthzocker build -t orchidhaven:1.0.0 .


Screenshots
Inside the /Docs folder:

Orchid-haven-ec2.png – Running EC2 instance showing public IP
Folder setup.png – Project Folder setup
Dockerfile setup.png – Dockerfile contents
Docker build.png – Docker build success
Running container.png – Running container screenshot
Website Screenshot.png – containerized Nginx web server static website 




 
=======
README
Orchid Haven Docker Project

This project sets up a containerized Nginx web server to host a static website for Orchid Haven, a shortlet apartment brand. The server is deployed using Docker, and the project demonstrates infrastructure automation and reproducible web hosting using best practices.

Project Folder Structure;

📁 orchid-haven-docker 🗄️Dockerfile 🗄️nginx.conf 🗄️index.html 🗄️styles.css 🗄️README.md

Steps to deploy the static website on an EC2 instance using Docker.

Step 1 --- Launch an AWS EC2 instance (Amazon Linux 2023) - Docker installed and running - Security Group open on port 80 for HTTP access

Step 2 --- Clone the Repository

git clone https://github.com//orchid-haven-docker.git

cd orchid-haven-docker

Step 3 --- Build the Docker Image

docker build -t orchidhaven:1.0.0 .

Step 4 --- Run the Container

docker run -d --name orchidhaven -p 80:80 --restart unless-stopped orchidhaven:1.0.0

Step 5 --- Access the Website; Visit your EC2 public IP: http://

Check container health; curl http://localhost/healthzocker build -t orchidhaven:1.0.0 .

Screenshots Inside the /Docs folder:

Orchid-haven-ec2.png – Running EC2 instance showing public IP Folder setup.png – Project Folder setup Dockerfile setup.png – Dockerfile contents Docker build.png – Docker build success Running container.png – Running container screenshot, Website Screenshot.png – containerized Nginx web server static website.
>>>>>>> 6e439f5 (changes made to README.md file and Screenshot folder added)
