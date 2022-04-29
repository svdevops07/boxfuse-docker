# boxfuse-docker
task for lection 6. Boxfuse in Java
## How to run

```
# Download
git clone https://github.com/svdevops07/boxfuse-docker.git
cd boxfuse-docker/

# Run on ubuntu
docker build -f Dockerfile-ubuntu -t boxfuse-ubuntu:0.1 .
docker run -d -p 8080:8080 boxfuse-ubuntu:0.1

# Run on tomcat
docker build -f Dockerfile-tomcat -t boxfuse-tomcat:0.2 .
docker run -d -p 7779:8080 boxfuse-tomcat:0.2
```

## Resource
from DevOps-school course
