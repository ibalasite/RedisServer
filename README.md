# RedisServer

* for dockerfile build
```command
mkdir ~/redis
cd ~/redis
git clone https://github.com/ibalasite/RedisServer.git
docker build -t="test/redis"  .
mkdir ~/share
docker run -dti -v ~/share:/share test/redis
```
* for docker hub
```
docker run -dti -v ~/share:share evansking/redis
```
