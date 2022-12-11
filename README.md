Install Node.js
Create app.js file
Create Dockerfile
Creating a package.json file with all needed metadata by: **npm init**
Install Express web application framework: **npm install express**
Build docker image: **docker build -t user1name/devops .**
Push docker image to dockerhub:
    **docker login**
    **docker push user1name/devops**
Run container with cpu and memory constraints: **docker run -m 20m --cpus=0.1 -d -p 80:80 --name node-app devops-l1**
