# docker nginx-1.18.0 php72
docker nginx-1.18.0 php72

# file => conf.d/default.conf


## uncomment no persistent connection nodejs

```
#least_conn;     
```

## uncomment persistent connection php session

```
#hash $remote_addr consistent; 
```

## change php version 
```
image: wachira90/php:7.1
image: wachira90/php:7.2
image: wachira90/php:7.3
image: wachira90/php:7.4    
```

## run 

```
  docker-compose up -d
```

## stop 

```
  docker-compose stop 
```

## restart

```
  docker-compose restart
```

## shutdown

```
  docker-compose down
```

## url

```
http://localhost:7000

http://localhost:7000/info.php
```

### modby => wachira90@yahoo.com

### docker-nginx180-php72
