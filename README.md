# 阿里云Centos6.7 环境搭建
> 记录阿里云ECS的javaweb开发环境的搭建，分布式等一系列操作。

**配置如下**

* Apache Tomcat/8.5.15
* Oracle1.1.2
* Nginx
* JDK1.8
* 设置了Tomcat和Nginx的启动项
   ----
   
   
# 基础环境配置
[阿里云ESC搭建javaWeb环境](http://blog.csdn.net/qq_15807167/article/details/70941644)

此博文介绍了如下内容：
* java 环境配置
* Mysql 环境配置
* tomcat 环境配置
[Centos7 tomcat开机自启配置](http://www.028888.net/archives/2017_02_1722.html)

[Oracle环境配置](http://www.cnblogs.com/crazyMyWay/articles/4371984.html)

# 卸载rpm安装包操作
[卸载rpm安装包](http://blog.csdn.net/qq_15807167/article/details/72872563)

# 阿里云安全组（开放8080端口）
[开放8080端口](http://blog.csdn.net/swl979623074/article/details/71910308)

# Nginx阿里云配置
```
// 进行安装OpenSSl和Zlib的库
yum -y install zlib zlib-devel openssl openssl--devel  

```

[Nginx安装前Pre依赖库安装](http://blog.csdn.net/liujihaozhy/article/details/42271253)
或使用[Prce安装包编译安装](http://jingyan.baidu.com/article/f7ff0bfc6bc0472e26bb13bf.html)

[Nginx阿里云安装配置](http://www.cnblogs.com/nokiaguy/p/4703429.html)
[Nginx设置开机自启](http://www.jianshu.com/p/b5fa86d54685)

# MySQl配置

[设置远程访问](http://www.cnblogs.com/xyzdw/archive/2011/08/11/2135227.html)

------
# 更换为阿里提供的镜像
[镜像配置](https://market.aliyun.com/products/53400005/cmjj014846.html?spm=5176.2020520101.image.selectFromMarketplace.2x4LKn)
[镜像配置](https://market.aliyun.com/products/53400005/cmjj015046.html?spm=5176.2020520101.image.selectFromMarketplace.2O3xKI)
[目前使用的镜像](https://market.aliyun.com/products/53400005/cmjj010920.html?spm=5176.2020520101.image.selectFromMarketplace.1rfUCj)
