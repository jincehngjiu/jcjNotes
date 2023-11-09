# 一、linux安装redis

~~~markdown
1. yum install wget
2. cd ~
3. mkdir soft
4. cd soft 
5. wget https://download.redis.io/releases/redis-5.0.5.tar.gz
6. tar xf redis....tar.gz
7. cd redis/src
8. 看README.md
9. make
...  yum install gcc
... make distclean
10. make 
11. cd src ... 生成可执行文件
12. cd ..
13. make install PREFIX =/opt/mashibing/redis5
14. vi/etc/profile
... export REDIS_HOME=/OPT/mashibing/redis5
... export PATH=$PATH:$REDIS_HOME/bin
15. cd utils
16. ./install_server.sh
 ①. 一个物理机中可以有多个redis实例(进程),通过port区分
 ②. 可执行程序就一份在目录, 但是内存中未来的多个实例需要各自的配置文件


~~~

