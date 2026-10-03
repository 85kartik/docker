# Docker Commands 🐳

## Create Image

```bash
docker build -t <image-name> .
```

## Create Container

```bash
docker run -d --name <container-name> <image-name>
```

## Start Container

```bash
docker start <container-name>
```

## Stop Container

```bash
docker stop <container-name>
```

## Restart Container

```bash
docker restart <container-name>
```

## Delete Container

```bash
docker rm <container-name>
```

## Force Delete Container

```bash
docker rm -f <container-name>
```

## Delete Image

```bash
docker rmi <image-name>
```

## Force Delete Image

```bash
docker rmi -f <image-name>
```

## List Images

```bash
docker images
```

## List Running Containers

```bash
docker ps
```

## List All Containers

```bash
docker ps -a
```

## View Container Logs

```bash
docker logs <container-name>
```

## Access Container

```bash
docker exec -it <container-name> bash
```

## Rename Container

```bash
docker rename <old-name> <new-name>
```

## Remove Unused Images

```bash
docker image prune
```

## Remove Stopped Containers

```bash
docker container prune
```

## Remove Unused Resources

```bash
docker system prune
```
