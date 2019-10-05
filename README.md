```
yarn install
```

Build docker image

```
docker build -t node-app
```

Run docker image

```
docker run -p 12345:8080 -d node-app
```

Access app on http://localhost:12345

Stop docker image

```
docker stop <CONTAINER_ID>
```

List all your docker images with `docker ps`
