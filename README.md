# Docker base for CakePHP 3.7+

## Usage 

```
docker-compose build

docker-compose up -d

docker exec -it cakephp /bin/bash

cd /tmp/mysql-5.7.27-linux-glibc2.12-x86_64/bin

./mysql -u developer -h mysql -p

Passwd : dev123

```

### List all containers
```
docker ps
```

### Execute a command in a container
```
docker exec <container-id> composer update 
```

## Inspiration

Inspiration, code snippets, etc.
* [Cloud 66](https://blog.cloud66.com/deploying-your-cakephp-applications-with-cloud-66/)
