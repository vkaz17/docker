# docker
#### Docker Build
```
cd ${project.dir}
docker-compose build
```

#### MySQL
```
# MySQL Start
docker-compose up -d mysql

# MySQL Server Login
mysql --host=127.0.0.1 -u root -p

# Docker Login
docker exec -it mysql /bin/bash
```

#### Redis
```
# Redis Start
docker-compose up -d redis

# Docker Login
docker exec -it redis /bin/bash

# Redis Login
redis-cli
```

#### Nginx
```
# Nginx Start
docker-compose up -d nginx

# Docker Login
docker exec -it nginx /bin/bash

# Static Contents Access
curl localhost:8080/test.html
```