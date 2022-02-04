### Docker Commands
This file is consist of docker commands for using and accessing faster. You are requested to use it with your own risk, 
 * docker ps
 * docker run <image_name>
 * docker create <image_name>
 * docker start -a <container_id>
 * docker start <container_id>
 * docker run -it ubuntu bash
 * docker ps --all || docker ps -a
 * docker system prune // removes all containers, networks, images, build caches
 * docker logs <container_id>
 * docker stop <container_id>
 * docker kill <container_id>
 * docker exec -it <container_id> <command> // -i -t , i->; exec -> execute 
 * docker exet -it <container_id> sh // sh for bash command, we call also use bash instead of sh
 * docker build .
 * FROM, RUN, CMD -> instruction -> Dockerfile keyword
 * Base Image -> ubuntu 
 * docker build -t <docker_id>/<repo_or_project_name>:<version> . // tag a docker image, the last dot is importan as context 
 * docker run -p <host_port>:<container_port> <image_id> 

 * docker build -f  Dockerfile.dev . // for specific Dockerfile build
 * docker run -v /app/node_modules -v $(pwd):/app <image_id> // -v flag for volume reference/ to link a volume
 *  

#### Tips: 
* CTRL + d -> for exiting Linux CLI
* exit -> for exiting Linux CLI  
* sh -> bash, powershell, zsh, sh
* check nodeJsApp for a demo
* alpine -> pretty much min installed programs as possible
* 
