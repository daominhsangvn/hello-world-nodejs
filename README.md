# Hello world node js app with docker
- Build image: `docker build -t hello-world-nodejs .`
- Push image to hub:
```
$ docker login
$ docker tag hello-world-nodejs:latest daominhsangvn/hello-world-nodejs:latest
$ docker push daominhsangvn/hello-world-nodejs:latest
```