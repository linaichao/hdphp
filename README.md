
# HDPHP
后盾网HDPHP框架是一个为用PHP程序语言编写网络应用程序的人员提供的软件包。 提供强大的、完整的类库包,满足开发中的项目需求,可以将需要完成的任务代码量最小化，大大提高项目开发效率与质量。高效的核心编译处理机制让系统运行更快。
做为优秀的框架产品,在系统性能上做的大量的优化处理,只为让程序员使用HDPHP框架强悍的功能同时,用最短的时间完成项目的开发。


## 全面的WEB开发特性支持
* HDPHP是完全免费的，你不用担心任何版权问题
* 提供多项优化策略，速度非常快
* 采用 MVC 设计模式
* 生成干净的 URL
* 支持Memcached与NoSql
* 高效的HDView模板引擎
* 拥有全范围的类库
* 通过自定义类库、辅助函数来实现框架的扩展
* 对象关系映射(ORM)

##安全性
框架在系统层面提供了众多的安全特性，确保你的网站和产品安全无忧。这些特性包括：

* COOKIE加密处理
* 数据预处理机制
* XSS安全防护
* 表单自动验证
* 强制数据类型转换
* 输入数据过滤
* 表单令牌验证
* 防SQL注入
* 图像上传检测


##商业友好的开源协议
HDPHP遵循Apache2开源协议发布。Apache Licence是著名的非盈利开源组织Apache采用的协议。该协议和BSD类似，鼓励代码共享和尊重原作者的著作权，同样允许代码修改，再作为开源或商业软件发布。


> V5课堂从12.20开始开课，本期讲解内容就是HDPHP，同时有问题解答环节！
***


###以往更新
2014.1.4

```
1. $this->_post()这种调用方式废弃了
2. 自定义session处理方式发生改变，请参考手册
3. 升级百度编辑器ueditor至1.3.6版本
4. 自动验证增加身份证验证
5. 自动验证方法maxlen与minlen改变验证字符长度(支持中文)
```

2013.12.30

```
1. 修改success.html与error.html样式
2. 修改sessionFile.class.php目录问题
3. 增加捕获致命性错误问题
```

2013.12.25

```
1. 修正session文件创建失败的问题
2. 添加cookie支持
3. 优化session处理机制
4. 重新定义session的配置项设置
5. 新增cookie配置项设置
```
2013.12.21

```
1. 修改在应用组模式时，配置auto_load_file失败的问题
2. 压缩HDPHP数据，去除一些不用的JS插件如ICHECK
3. 修改模板标签加载失败问题
4. 修复Data::parentChannel()由于使用static在生成全站静态时造成的问题
5. hdui中添加slide轮换效果
```
2013.12.19

```
1. 增加应用分组变量g,分组应用管理更加强大
2. 增加目录安全文件创建方法Dir::safeFile
3. 更新HDPHP手册
4. 优化Html静态文件生成类
5. 修复js自动验证confirm不起作用问题
```
