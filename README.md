# python-web-app-docker-compose

Python web application running on Docker Compose. The application uses the Flask framework and maintains a hit counter in Redis.

start up your application by running 
docker-compose up

To build a docker containers in detached mode
docker-compose up -d

To rebuild a docker container in detached mode
docker-compose up --build -d

Lists containers
docker-compose ps
