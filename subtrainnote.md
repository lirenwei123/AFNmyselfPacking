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

# 7. sizeWithAttributes 单行时

# 8. 多行时

# boundingRectWithSize:CGSizeMake\(kScreen\_Width, MAXFLOAT\) options:NSStringDrawingUsesLineFragmentOrigin attributes:@{NSFontAttributeName:\[UIFont systemFontOfSize:14\]} context:nil\].size

# 9.PCH设置路径时，只要复制\/工程名／...\/...prefix.pch

## 10.关于xib的一点总结：

注册的时候还是用xib注册，跟自己一类的类型的文件相连的时候，点击自己去连clas，不要点flieower去连class。

> ## 11.UITableViewCell \*cell =\[tableView dequeueReusableCellWithIdentifier:ID` forIndexPath:indexPath]`;\/\/这是要注册的才行

