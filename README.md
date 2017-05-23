```
docker build -t my-redis .
docker run --name some-redis -p 6379:6379 -v /home/docker/data:/data -d my-redis
```
