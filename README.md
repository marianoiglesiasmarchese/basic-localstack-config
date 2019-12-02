# basic-localstack-config
Basic local stack aws services configuration

# run

```bash
docker-compose up
```

# If you did some change and you wanna see them on the container

```bash
docker-compose up --force-recreate --build
```

# to check services
```
http://localhost:8080
```

# to check content of a service

```
http://localhost:4572/test-bucket/
```