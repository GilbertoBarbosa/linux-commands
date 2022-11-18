Pull image
```
docker pull <imageName>
```

Runner container
```
docker run -t -i <imageName>
```

Runner container with local volume
```
docker run -d --name <name> -v <pathLocalVolume>:<pathContainerVolume> -it <imageName>
```
