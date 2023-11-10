# 一、linux 笔记

## 1.查看密码

```markdown
1. 用户名在/etc/passwd 这个文件中,密码在/etc/shadow 中;
   cat /etc/passwd
   cat /etc/shadow
2. 为了安全，系统将明文密码进行了加密。接下来我们看看系统使用了什么加密方式;  
   authconfig --test | grep hashing
3. 找到密码利用在线解密工具即可哈
```

## 2.查看目录磁盘空间

~~~markdown
1. du -ah --time --max-depth=1 /tmp/order/* | sort -hr | head -n 10
~~~

