# Build Docker container

```
docker build -t udacity-self-driving-car .
docker run -it --memory=10g -p 8888:8888 -v "$(pwd)":/src --name udacity udacity-self-driving-car /bin/bash
```