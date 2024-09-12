# minesweeper
Repository to host ros packages for 2024 Aqualia team

## How to run Docker Conatiner 
After cloning this repo 
`docker built -t <image name > .`
OR alternatively you can (Not recommended)
`docker pull docker push studhamza/ros:noetic-minesweeper`

### NO GUI 
* List All images
  `docker images -a`
* Run Images in interactive mode
  `docker run --name <any_name> -it <docker image name>
* Start Container, (us `docker ps -a` to find container id)
  `docker start <container_id>`
* In another terminal start a interactive shell
  `docker exec -it <container_id> bash`
* Now you `source ./ros_entrypoint.sh` and cd to your working directory 
* For more commands check this out [Docker commands](https://github.com/noshluk2/ros1_wiki/blob/main/docker/commands.md)
