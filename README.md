# mysql_with_docker_compose
docker-composeを利用したMySQL起動方法メモ。

##Usage
起動
```bash
docker-compose up -d --build
```
接続
```
mysql -uroot --protocol=TCP
```

停止
```
docker-compose down -v
```
