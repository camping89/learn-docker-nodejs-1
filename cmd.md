docker build -t hello-world .
docker images
docker container run -p 4001:8081 hello-world

docker rmi devopsveekvn/sample

docker tag hello-world devopsveekvn/sample
docker push devopsveekvn/sample:latest
docker pull devopsveekvn/sample:latest
