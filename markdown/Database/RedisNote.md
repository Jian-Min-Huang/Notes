##### delete keys
```sh
$ redis-cli KEYS "prefix:*" | xargs redis-cli DEL
$ redis-cli -h 10.0.0.3 -p 6379 KEYS "Lotto:BetType:102:PAND" | xargs redis-cli -h 10.0.0.3 -p 6379 DEL
```

##### start redis server
```
$ redis-server config/redis.conf
```