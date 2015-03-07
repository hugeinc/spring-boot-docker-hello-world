SPRING BOOT AND DOCKER
================

Installation
-----------------

* Build the application
```sh
cd spring-boot-docker-hello-world
mvn clean install
cd target 
docker build -t spring-boot-docker-hello-world .
```

* Deploy the Docker Container
```sh
docker images
docker run -p 8080:8080 <image id>
```

Check it
------------------
Open a browser:  http://localhost:8080