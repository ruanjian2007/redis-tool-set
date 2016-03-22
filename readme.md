# Redis tool list #

Here is a Redis tool list. I hope you will find one or two of them that you'd like to try out.

- [Redis tool list](#Redis tool list)
	- [Redis Variety](#redis variety)
	- [Redis Proxy](#redis proxy)
	- [Redis data migration](#redis data migration)
	- [Redis monitor](#redis monitor)
	- [Redis Admin Web UI](#redis admin web ui)
	- [Redis ecosystem](#redis ecosystem)

---
## Redis Variety
* [AliRedis](http://blog.sina.com.cn/s/blog_e59371cc0101br74.html) - AliRedis, which is developed by Alibaba, use a new nginx-like one-master-multi-worker framework, in order to get full use of the CPU cores.
* [Qedis](https://github.com/loveyacper/Qedis) - A C++11 implementation of Redis server.

---
## Redis Proxy
* [bilitw](https://github.com/anewhuahua/bilitw) - bilitw (bilibili twemproxy), which introduce multi process of twemproxy(one master and mutli worker), is order to get full use of the CPU cores.
* [Corvus](https://github.com/eleme/corvus) - A fast and lightweight Redis Cluster Proxy for Redis 3.0.
* [twemproxy](https://github.com/twitter/twemproxy) - A fast, light-weight proxy for memcached and redis.

---
## Redis data migration
* [redis-port](https://github.com/CodisLabs/redis-port) - parse redis rdb file, sync data between redis master and slave
* [redis-migration](http://www.bitstech.net/2016/03/03/redis-migration/) - A Chinese blog declares its tool(redis-migration, developed by Netease Inc.) is better than redis-port and not open source.
* [redis rdb file splitter](http://blog.nosqlfan.com/html/4092.html) - In this Chinese blog you will get a script to split Redis rdb db file.

---
## Redis monitor
* [redis-monitor](https://github.com/LittlePeng/redis-monitor) - base RedisLive,monitor multiple redis-server in product enviroment: monitor multiple redis-instance in one page; monitor memory,comand per sec,HitRate,keyspace, master-slave change,expire; sms alert when crash , master-slave stats changed.

---
## Redis Admin Web UI
* [cachecloud](https://github.com/sohutv/cachecloud) - A private redis cloud platform developed by Sohu Inc.
* [RedisReact](https://github.com/ServiceStackApps/RedisReact) - Redis React is a simple user-friendly UI for browsing data in Redis servers which takes advantages of the complex type conventions built in the ServiceStack.Redis Client to provide a rich, human-friendly UI for navigating related datasets, enabling a fast and fluid browsing experience for your Redis servers. Its related project is [ServiceStack.Redis](https://github.com/ServiceStack/ServiceStack.Redis).

---
## Redis ecosystem
* [awesome-redis](https://github.com/zhemingwang/awesome-redis) - A curated list of amazingly awesome redis and redis ecosystem resources.

---
*written by Alex Stocks on 2016/03/22*