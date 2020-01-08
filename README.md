# docker-lamp

Docker example with **L**inux **A**pache, **M**ySql 8.0 and **P**hp

### Installed addons

#### misc

- phpMyAdmin

#### php
- mysqli
- pdo-mysql

## Configuration

- change `php.ini` as you like

## run

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:18000](http://localhost:18000)

Open web browser to look at a simple php example at [http://localhost:10080](http://localhost:10080)

Run mysql client:

- `docker-compose exec mysql mysql -u root -p` 

## stop

```
docker-compose down
```


