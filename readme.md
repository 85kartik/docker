# 1. Create a Docker Image
docker build -t <image-name> .

# 2. Create a Container from an Image
docker run -d --name <container-name> <image-name>

# 3. Delete an Image
docker rmi <image-name>

# 4. Delete a Container
docker rm <container-name>

# 5. Force Delete an Image
docker rmi -f <image-name>

# 6. Force Delete a Running Container
docker rm -f <container-name>

# 7. Start a Container
docker start <container-name>

# 8. Stop a Container
docker stop <container-name>

# 9. Restart a Container
docker restart <container-name>

# 10. List All Docker Images
docker images

# 11. List Running Containers
docker ps

# 12. List All Containers
docker ps -a

# 13. View Container Logs
docker logs <container-name>

# 14. Access Container Terminal
docker exec -it <container-name> bash

# 15. Rename a Container
docker rename <old-name> <new-name>

# 16. Remove Unused Images
docker image prune

# 17. Remove Stopped Containers
docker container prune

# 18. Remove Unused Docker Resources
docker system prune
