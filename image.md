```bash
docker image history <image>
docker image inspect <image>
docker image tag <image> <tag>

# remove dangling tags
docker rmi -f $(docker images -f "dangling=true" -q)
```
