------
Manual Build and Start : 

Clean and Build Jar --> mvn clean install 

Start jar file --> java -jar .\*.jar

------

Docker Build and Start : 

sudo docker build -t spring-app .
sudo docker run -d -p 8080:8080 spring-app
sudo docker ps

------
