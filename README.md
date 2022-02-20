# Important Commands For Docker

1. Docker Show Running containers
    - `docker container ls`
1. Docker Show All(running + stopped ) containers
   - `docker container ls -a`
1. Docker container create and keep running at backword
   - `docker container run -itd  <docker_image>`
1. Docker container create and get inside container ie. here image is ubuntu os
   - `docker container run -itd ubuntu /bin/bash`
1. Docker Stop running container
   - `docker container stop <container_name_or_id>`
1. Docker remove Running containers forcefully
   - `docker container rm <container_name_or_id> -f`
1. Docker remove stopped container 
   - `docker container rm <container_name_or_id>`
1. Docker start stopped container 
   - `docker container start <container_name_or_id>`
1. Docker container pause container
   - `docker container pause <container_name_or_id>`
1. Docker remove all stopped containers at once
   - `docker container prune`
1. Docker read all information about container ie. IP , Volume etc
   - `docker container inspect <container_name_or_id>`
1. Docker container rename 
   - `docker container rename <container_name_name_id>   <new_name>`
1. Docker container Provide name while creating new container 
   - `docker container run -itd --name <container_name>  <image>`
1. Docker get inside of running container
   - `docker container attach <container_name_or_id>`
1. Docker Volume Create
   - `docker volume create <volume_name>`
1. Docker volume attach to docker container (while creating only possible)
   - `docker container run -itd --name <container_name> -v <volume_name>:<mount_dir> <image>`
   


### **************************************************************** 


### Ref: https://dockerlabs.collabnix.com/docker/dca.html