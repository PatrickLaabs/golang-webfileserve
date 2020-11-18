# golang-webfileserve
simple app to serve files and show them inside the webbrowser

## running straight with golang

1. pull this repo
2. run "go run main.go"

Access webpage via http://localhost:8100/files

Adding files to the /files folder will show them into webpage

## Running docker image

1. run "go build" inside this folder
2. run "docker build -t golang-webfileserve ."
3. run "docker run -d -p 8100:8100 golang-webfileserve"

Access webpage via http://localhost:8100/files

## running container from dockerhub

1. docker pull paddybn/golang-docker-app:latest
2. run "docker run -p 127.0.0.1:8100:8100/tcp -d paddybn/golang-docker-app:latest"

Access webpage via http://localhost:8100/files
