##### delete keys
```sh
$ redis-cli KEYS "prefix:*" | xargs redis-cli DEL
```

##### start redis server
```
$ redis-server config/redis.conf
```