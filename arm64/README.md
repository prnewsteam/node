```
docker buildx build --platform linux/arm64 -t prnewsio/node:14.15.3.arm --force-rm --no-cache .
docker login -u="\$DOCKER_USERNAME" -p="\$DOCKER_PASSWORD"
docker push prnewsio/node:14.15.3.arm
```