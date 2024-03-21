## Simple node.js app with docker


### Helpful commands

To create Docker Image
```
docker build -t testApp .
```

To run Docker Image
```
docker run -p 4000:4000 testApp
```

To run Docker Image Container in BackGround
```
docker run -d -p 4000:4000 testApp
```

To see All Running Container
```
docker ps
```

To see All docker Image in your Local Machine
```
docker images
```

To Kill specific docker Container

```
#docker kill <container_id>
docker kill 71de81055cc6
```

