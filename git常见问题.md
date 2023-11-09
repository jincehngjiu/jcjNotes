# 一、git常见问题

## 1.clone github代码报错

~~~markdown
1. 拉取github代码报错: unable to connect to github.com: github.com[0: 140.82.113.3]: errno=Unknown error
~~~

- 确认是否能ping通哈

~~~markdown
$ ping github.com
Pinging github.com [20.205.243.166] with 32 bytes of data:
Request timed out.

~~~

-  git clone https://…

~~~markdown
$ git clone https://github.com/tom-wong168/knowledge-system.git
Cloning into 'knowledge-system'...
fatal: unable to connect to github.com:
github.com[0: 140.82.113.3]: errno=Unknown error

~~~

- 改https为git，git clone git://…

~~~markdown
$ git clone git://github.com/tom-wong168/knowledge-system.git
Cloning into 'knowledge-system'...
fatal: unable to access 'https://github.com/tom-wong168/knowledge-system.git/': Failed to connect to github.com port 443 after 21069 ms: Couldn't connect to server

~~~

- 重置 http.proxy

~~~markdown
$ git config --global http.proxy http://127.0.0.1:1080
---------------------------------
$ git config --global https.proxy https://127.0.0.1:1080
---------------------------------
$ git config --global --unset http.proxy
---------------------------------
$ git config --global --unset https.proxy
---------------------------------

~~~

~~~markdown
$ git clone git://github.com/tom-wong168/knowledge-system.git
Cloning into 'knowledge-system'...
fatal: unable to access 'https://github.com/tom-wong168/knowledge-system.git/': Failed to connect to github.com port 443 after 21071 ms: Couldn't connect to server
~~~

- 设置 http.sslVerify 为 false

~~~markdown
$ git config --global http.sslVerify "false"
---------------------------------
$ git config --global https.sslVerify "false"
---------------------------------
~~~

~~~markdown
$ git clone git://github.com/tom-wong168/knowledge-system.git
Cloning into 'knowledge-system'...
remote: Enumerating objects: 69, done.
remote: Counting objects: 100% (69/69), done.
remote: Compressing objects: 100% (50/50), done.
remote: Total 69 (delta 14), reused 57 (delta 8), pack-reused 0
Receiving objects: 100% (69/69), 4.52 MiB | 42.00 KiB/s, done.
Resolving deltas: 100% (14/14), done.

~~~

### 1.1致命错误：无法连接到github.com：github.com[0：140.82.121.4]：错误号=未知错误

~~~markdown
1. 问题是git端口是受限的，这就是为什么它给出了一个错误！因此，您可以使用以下命令修复它：
git config --global url.https://github.com/.insteadOf git://github.com/
~~~

### 1.2 fatal: unable to access ‘https://github.com/…’: [OpenSSL](https://so.csdn.net/so/search?q=OpenSSL&spm=1001.2101.3001.7020) SSL_read: Connection was reset, errno 10054

~~~markdown
1. 【产生原因】一般是因为服务器的SSL证书没有经过第三方机构的签署，所以才报错【解决方式】解除ssl验证后，再次git即可
git config --global http.sslVerify false
~~~



## 2.设置用户信息

-- 设置用户名

~~~markdown
1. git config --global user.name "Your Name"
~~~

-- 查看用户名

~~~markdown
2. git config --global user.name 
~~~

