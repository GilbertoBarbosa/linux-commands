Docker version
```
docker version
```

Pull image
```
docker pull <imageName>
```

List running containers
```
docker ps
```

List containers
```
docker ps -a
```

Runner container
```
docker run -dt --name <containerName> -i <imageName>
# or
docker container <containerName>
```

Runner container with local volume iterative mode
```
docker run -it --name <name> --mount type=bind,source=<pathLocalVolume>,target=<pathContainerVolume> <imageName>
# or
docker run -it --name <name> -v <pathLocalVolume>:<pathContainerVolume> <imageName>
# or (background)
docker run -dit --name <name> <image>
```

Exec container (Linux)
```
docker exec -it <containerName> /bin/bash
```

Create volume
```
docker volume create <volumeName>
```

Delete volume
```
docker volume rm <volumeName>
```

List volumes
```
docker volume list
```

Inspect volume
```
docker volume inspect <volumeName>
```

Start/Stop container
```
docker container start <containerName>
docker container stop <containerName>
```

Create image in the current directory
```
docker build -t <imageName> .
```

List docker networks
```
docker network ls
```

Create new network
```
docker network create <networkName>
```

Docker inspect
```
docker inspect <containerName>
```

Disconnect/connect network
```
docker network disconnect <network> <container>
docker network connect <network> <container>
```
