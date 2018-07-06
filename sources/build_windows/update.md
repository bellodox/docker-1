This image is hosted on docker hub :
https://hub.docker.com/r/ignitioncoin/build_windows/

To update it, edit the Dockerfile and run
```
docker login
docker build . -t ignitioncoin/build_windows
docker push
```