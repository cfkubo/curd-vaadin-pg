# curd-vaadin-pg


```
docker run --name my-postgres -e POSTGRES_PASSWORD=password -d postgres
```

```
CREATE ROLE admin WITH LOGIN PASSWORD 'password';
ALTER ROLE admin WITH SUPERUSER;
```

```
mvn clean install
mvn spring-boot:run
```

