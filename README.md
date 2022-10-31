## DevOps Fundamentals docker lab
### To run this project in docker, use:

```shell
docker run -d -p 80:3000 --cpus="2" --memory="200m" jedich/devops-fundamentals-docker
```

### Or build locally:
```bash
docker build -t lab1 .
docker run -d -p 80:3000 --cpus="2" --memory="200m" lab1
```