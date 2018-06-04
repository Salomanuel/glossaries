# install Redis

1. `$ wget http://download.redis.io/redis-stable.txt`
2. `$ tar xvzf redis-stable.tar.gz`
3. `$ cd redis-stable`
4. `$ make`

# start Redis
`$ redis-server`

# check if Redis is working
`$ redis-cli ping`
`PONG`

```
  $ redis-cli
    redis> ping
    PONG
    redis> set banana tasty
    OK
    redis> get banana
    "tasty"
```
