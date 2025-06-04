# arghavan.devoopd.docker.1
1-
docker pull nginx
docker images
docker run --name nginx -dp 8080:80  nginx
docker run --name nginx-number2 -dp 8081:80  nginx
docker ps
docker logs nginx8080
docker logs nginx8081
docker stop nginx-number2
docker stop nginx
docker rm nginx-number2
docker rm nginx
