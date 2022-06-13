# docker-whale

Run me : `docker run -p80:80 docker-whale:v1.0`

Build me: `docker build -t docker-whale:v1.0 .`

Login Docker Hub: `docker login` -> input user/password

Tag a version and push to docker hub: 
- `docker image tag docker-example:v1.0 <username>/docker-whale:latest`
- `docker push <username>/docker-whale:latest`

Pull an image from docker hub: `docker pull <username>/docker-whale:latest`
