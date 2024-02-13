# AccWe Hospital
Cómo montar los Dockerfiles

Dockerfile.maven
```bash
docker build -t spring-container -f Dockerfile.maven . && docker run -d -p 8080:8080 spring-container
```

Dockerfile.mysql
```bash
docker build -t mysql-container -f Dockerfile.mysql . &&  docker run -d -p 3306:3306 mysql-container
```
