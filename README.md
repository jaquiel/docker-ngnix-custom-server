﻿# Nginx Custom Server
 
 ### Building

```
 $ docker build -t <NGIX_IMAGE_NAME> github.com/jaquiel/docker-nginx-custom-server
```

### Running

```
 $  docker run -it -p 80:80 --name <NGINX_CONTAINER_NAME> <NGINX_IMAGE_NAME> 
```

**OR** **(with --rm to remove the container after stop it)**


```
 $  docker run -it -p 80:80 --rm --name <NGINX_CONTAINER_NAME> <NGINX_IMAGE_NAME> 
```
