# Remote-Repository
//I am commiting to Features branch\\
//Docker Commands
#docker run ubuntu cat /etc/*release*
#docker ps
#docker ps -a
#docker run -d ubuntu
#docker run ubuntu:17.0 cat /etc/*release*
#docker run ubuntu sleep 100
#docker stop <Container Id>
#docker attach <Container Id>
#docker inspect <Container Id>
#docker run -p 8080:8080 jenkins
#docker run -p 8080:8080 jenkins
#docker run -p 8080:8080 -v /myhome/mydorectory:/var/jenkins_home -u root jenkins
#docker run -p 38282:8080 docker user-webapp:
  **//Docker file creation;**
#FROM ubuntu =====> "FROM" is a instruction & "ubuntu" is an argument
#RUN apt-get update
#RUN apt-get install python
#RUN pin install flask
#RUN pip install flask-mysql
#COPY ./opt/source-code
#ENTRYPOINT FLASK_APP=/opt/source-code/app.py flask run
  **//Docker Compose;**
#docker build <Docker file> -t Jaandhan/my-custom-app
#docker push Jaandhan/my-custom-app
#docker run -it ubuntu bash
#docker build . -t voting-app
#docker images
#docker run -d --name=redis redis
#docker run -p 5000:80 --link redis:redis voting-app
#docker run -d -p 5000:80 --link redis:redis voting-app
#docker inspect <Container Id>
#docker rm voting-app
#docker run -d --name=db postgres:9.4
#docker build . -t worker-app
#docker run -d --link redis:redis --link db:db worker-app
