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
docker run -t -i <imageName>
# or
docker container <containerName>
```

Runner container with local volume iterative mode
```
docker run -it --name <name> --mount type=bind,source=<pathLocalVolume>,target=<pathContainerVolume> <imageName>
# or
docker run -it --name <name> -v <pathLocalVolume>:<pathContainerVolume> <imageName>
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
