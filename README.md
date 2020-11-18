# golang-webfileserve
simple app to serve files and show them inside the webbrowser

## Running docker image

1. run "go build" inside this folder
2. run "docker build -t golang-webfileserve ."
3. run "docker run -d -p 8100:8100 golang-webfileserve"

Access webpage via http://localhost:8100/files
