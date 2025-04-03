## Why Docker?

### Dockerize an app

### Immediate file change (volumes)

### Use IDE in Docker

### Docker Compose

### Add more services (Redis)

### Debug Python code insdie a container

### docker build command
```
docker build -t fastapi-image .
```
### docker image run command
```
docker run --name fastapi-container -p 80:80 fastapi-image
```
## docker run with detach mode
```
docker run --name fastapi-container -p 80:80 -d fastapi-image
```
### Map our machine to container ( Mapping local volume to conatiner)

### Volume are prefffered mechanisham to store the data

### Attach local folder to container
```
docker run --name fast-container -p 80:80 -d -v $(pwd):/code fastapi-image
```
### Install 2 VS code extenstion Docker and Dev Container

