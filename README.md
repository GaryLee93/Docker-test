# Docker-test
try some ability of GitHub Action about docker

# How to Build Image and Run a Container with It.

1. Build an image named env-image
```
docker build -f Dockerfile -t env-image .
```

2. Run a container according to above image
```
docker run -p 5000:5000 --name sus_app env-image
``` 

3. Now you can go to 127.0.0.1:5000 to check this app
