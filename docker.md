Pull image
```
docker pull <imageName>
```

Runner container
```
docker run -t -i <imageName>
```

Runner container with local volume iterative mode
```
docker run -it --name <name> --mount type=bind,source=<pathLocalVolume>,target=<pathContainerVolume> <imageName>
```
