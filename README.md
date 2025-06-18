# Simple http server container

```bash
$ docker buildx build . --platform linux/amd64 --file Dockerfile --tag public/hello-world
$ docker run -it --rm --platform linux/amd64 -d -p 8080:80 --name hello-world public/hello-world:latest
```
