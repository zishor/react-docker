# React Docker Starter built with Maven
React in Docker Container

### Build with 
mvn clean package docker:build 

### Push to registry with 
mvn docker:push

### Run with
docker run -d -p 3000:3000 your-registry:5000/react-docker

# Dev
run "webpack -w" for live changes

run "node server.js" to run the server