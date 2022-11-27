# Docker Commands


### stop and delete all running containers

```
docker stop $(docker ps -aq)
```

```
docker rm $(docker ps -aq)
```
