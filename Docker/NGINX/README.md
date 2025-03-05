# NGINX

Set up an **NGINX** Server:

1. Copy [Dockerfile](./Dockerfile)
2. Build container: `$ docker build -t nginx:latest .`
3. Run container: `$ docker run --name nginx -p 8080:80 -d nginx:latest`
4. Open [http://localhost:8080](http://localhost:8080) or `http://host-ip:8080`
