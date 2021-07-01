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
