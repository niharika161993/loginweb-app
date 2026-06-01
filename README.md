# Java-Mysql-Simple-Login-Web-application

This is a simple demonstration project to showcase conatinerization of Java web application and Mysql database in docker and Kubernetes environment.

mvn clean package

docker build -t my-webapp:latest .

docker ps 	

docker image ls

docker run -d -p 8080:8080 --name my-webapp 

docker ps 

link ---- /LoginWebApp
