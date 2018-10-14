# KOA BACKEND WITH DOCKER

```bash
$ docker build -t <image-name> .
$ docker run -p3000:3000  --entrypoint="nodemon" -v`pwd`:/app <image-name>:latest
```