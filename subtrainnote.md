# 1.关于xib那些事：

### 快捷键：comand +enter\/ comand+alt+enter 在xib中切换一个窗口

# 2.自己的小错误总结

1关于文件操作write to file 不能写入到当前工程中，reson:程序在运行中，

2.沙河中的绝对路径不要去操作，因为下次开程序时绝对路径会改变,旧的所有文件复制到新的绝对路径中，而就的绝对路径及文件就消失了，这是ios8之后的新特性。

**\/Users\/rwli\/Library\/Developer\/CoreSimulator\/Devices\/76578239-AAF3-42C0-8ECA-C57763A52DCE\/data\/Containers\/Data\/Application\/**`F179909F-A56B-4E2F-BB16-D7DB3CAEE692`**\/Documents\/www.baidu.com**

# 3.一定要记住，在对请求后的数据进行解析时，解析接受到类型要注意

**Domain=com.alamofire.error.serialization.response Code=-1016 "Request failed: unacceptable content-type: **`text/plain`**"**

# 4.已经无数次把自己创建的对像不分配内存了，所以报错nil

# 5.不雅再写错别字了～～｀



# 6.NSinteger 设置为0的时候，return nil   important~~

