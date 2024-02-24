# docker-nginx-hello-world

# To properly create your container in system Windows:
1. Go to directory in shell
2. Write command: 
    docker run --name container_name -v .\index.html:/usr/share/nginx/html/index.html -p 8080:80 -d nginx:alpine
    Example:
    docker run --name nginx-hello-world -v .\index.html:/usr/share/nginx/html/index.html -p 8080:80 -d nginx:alpine