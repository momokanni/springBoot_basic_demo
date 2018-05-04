# springBoot_basic
`本例为springBoot2.0基础demo  `
`后续会添加：Spring security,solr,以及对小程序的支持`

### redis安装：[安装文档](http://blog.csdn.net/unix21/article/details/9526295 "安装文档")
redis可视化操作工具：RedisDesktopManager<br/>
redis安装配置过程需要注意一点：ping不通端口，修改配置文件 bind：127.0.0.1，这个IP要改为服务器IP，注释掉不好使。

### nginx安装：[安装文档](https://www.jianshu.com/p/d5114a2a2052 "安装文档") ，[服务配置](https://www.cnblogs.com/riverdubu/p/6426852.html) 
#### 注：
>1、打开gzip压缩。</br>
>2、跨域请求</br>
>3、websockt隧道</br>
>4、nginx缓存，且个人建议缓存放置在/dev/shm/目录下，此目录下缓存文件直接保存到服务器缓存中，读写速度快，缺点：服务器重启缓存文件丢失。</br>
>5、动静分离</br>
>6、防止SQL注入、Dos攻击</br>
>7、设置单位时间相同IP请求次数</br>
>8、清除缓存purge</br>
>9、允许打开文件最大数 cat /proc/sys/fs/file-max</br>
>9、max_fails=1 fail_timeout=30s proxy_connect_timeout

#### 需要了解的Spring知识点为：SpringAOP、Spring配置方式（1.组件扫描、自动配置，2.JavaConfig）、Spring缓存注解
#### websocket 采用的是H5标准,不是sockJS
#### logback 将程序错误异常发送邮箱时，163邮箱设置，密码需为"[客户端授权密码](http://mail.163.com)"
#### [微信SDK](https://github.com/Wechat-Group/weixin-java-tools/blob/master/readme.md)
#### 微信支付</br>
```<dependency> ```</br>
```  <groupId>cn.springboot</groupId> ```</br>
```  <artifactId>best-pay-sdk</artifactId> ```</br>
```  <version>1.1.0</version> ```</br>
``` </dependency> ```
