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


## Conceptos a añadir

[ESP](/)
Teniendo en cuenta que es un proyecto a gran escala optaría por el uso de
repositorios genericos junto a un CRUD para evitar el código repetitivo, además de uso de un DTO para agilizar las peticiones para el frontend.

[ENG](/)
Knowing the project is a large scale project i would consider using generic repositories with CRUD to avoid making junk code,
also i would try to make some DTO requests for the Frontend to make things easier.