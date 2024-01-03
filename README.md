# docker-ecs-jenkins


## Test locally in Docker

```
docker build -t myimage .
```

```
docker run -d --name mycontainer -p 8080:8080 -p 50000:50000 myimage
```
```
http://127.0.0.1:8080
```
