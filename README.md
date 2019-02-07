# mysql_with_docker_compose
How to start MySQL using docker-compose.

## Usage
start
```bash
docker-compose up -d --build
```
connect
```
mysql -uroot --protocol=TCP
```

stop
```
docker-compose down -v
```
