# Docker Song webpage

Simple HTML page containerized using Docker and Nginx.

## How to run:
bash...
docker build -t song-app .
docker run -d -p 8080:80 song-app
