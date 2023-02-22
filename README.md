# PYTHON-FLASK-POSTGRES-NGINX-ADMINER (DOCKER)

### Development up

```
docker-compose up -d 
```
> uses standard docker-compose.yml and .env file

### Production up

```
docker-compose -f docker-compose.prod.yml --env-file .env.prod up
```
> uses prod docker-compose.prod.yml and .env.prod file
