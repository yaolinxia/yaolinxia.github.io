---
layout: post
title: "SSH"
tag: Linux
---
## 1.  目录基本操作

## SSH相关操作：

- ssh [-l login_name][-p port] [user@]hostname

  ~~~
  ssh ubuntu@192.168.0.199
  ~~~

- ubuntu中将本地文件上传到服务器

  在本地的终端下，不是在服务器上。

  ~~~
  scp -r localfile.txt username@192.168.0.1:/home/username/ 
  ~~~

  ![](https://ws1.sinaimg.cn/large/e93305edgy1fwkst1a498j21hc0u0npf.jpg)

  将本地文件拷贝到服务器端docker中

~~~
scp -r -P 222 doc_imgs/ root@192.168.68.151：/usr/local/src
~~~

**注意⚠️**：后面的冒号要是英文的，目录要正确





注意：P一定要大写！！！！！，否则，拒绝访问！！！！！**

- ubuntu将服务器上文件拷贝到本地

~~~
scp -r —P 222 root@nju-vm:/usr/local/src/universal_cnn/ckpts/ /usr/local/src/data
~~~

- 

### 参考网址：

- https://blog.csdn.net/renyule/article/details/78949873
- <http://irwenqiang.iteye.com/blog/1151980>
- <https://www.zhihu.com/search?type=content&q=%E5%8D%B7%E7%A7%AF%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C>（知乎）


