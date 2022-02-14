# Docker Commands

### Pull Docker Image
`docker image pull $imageName`

### List Docker Images
`docker images`

### Run Docker Container Example 1
`docker container run -itd --name web-server-nginx -p 8080:80 nginx:latest`\
-d = detatched (will continue to run in the background)\
-i = interactive

### Run Docker Container Example 2
`docker container run -itd --name my_container $imageName`

### Check Running Docker Containers
`docker ps -a`

### Stop Docker Container
`docker container stop $containerName`

### Docker Build Image from Dockerfile
`docker build -t $imageName .`\
-t is Tag/name the image\
The . builds the image in the current directory - this can be changed to your specified location

### Docker Logs for Container
`docker logs $containerID`

### Tail Docker Logs for Container
`docker logs --follow $containerID`

### Tail x Number Log Lines for Container
`docker logs --tail $number $containerID`

### Enter Container with Bash
`docker exec -it $containerName bash`
