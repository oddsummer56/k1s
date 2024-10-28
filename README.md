# K1S
- https://hub.docker.com/_/httpd

# BUILD & RUN
```bash
$ docker build -t my-apache2 .
```

# 실행
```bash
$ docker run -dit --name my-running-app -p 8080:80 my-apache2
```

# 컨테이너 안으로
```bash
$ docker exec -it my-running-app bash
```

docker build -t my-apache2 .
docker run -dit --rm --name my-running-app -p 8949:80 my-apache2
