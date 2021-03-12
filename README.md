# docker-nginx
This repo hosts the nginx image for building our website with nginx


## Build docker image

Make sure to clone the dockerfile and put it on the source root. Then do:
```docker
docker build -t html-server-image:v1 .
```

## Run image

```docker
docker run -d -p 80:80 html-server-image:v1
```

## Go to website using cURL

```bash
curl localhost:80
```
