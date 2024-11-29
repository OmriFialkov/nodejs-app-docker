# nodejs-app-docker

class exer, has a link to docker hub image:

https://hub.docker.com/repository/docker/crazyguy888/nodejs_image/general

after cloning, run: 

docker build -t nodejs .
docker run -d -p 3000:3000 --name omri nodejs

or simply pull the image and use the 2nd command only.
