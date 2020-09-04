![b](https://s2.ax1x.com/2019/12/25/lFCd41.jpg "b")

### 之前看到有网友开发了一款PC端和VS Code插件版的小说阅读器（摸鱼神器Thief-Book），原创[链接地址](https://github.com/cteams/Thief-Book "链接地址")，但是很可惜的是没有IDEA版的，最近刚好比较闲，按照他的原型开发出了类似功能的IDEA插件。

------------
# 2020-09-04日更新记录





------------
# 2019-07-26日
------------
# 效果图
![t](https://s2.ax1x.com/2019/12/25/lFC6De.gif "t")

------------

![2](https://s2.ax1x.com/2019/12/25/lFChCt.jpg "2")

# 下载地址
[链接](https://github.com/yisier/thief-book-idea/releases/download/V1.0.0/thief-book-idea-1.0.0.jar "链接")

------------

## 使用教程
1).到release中下载jar包;

2).打开IDEA,找到setting 中的plugin，点击Install Plugin from disk选择下载的jar包，安装并重启IDEA;

3).进入IDEA的Setting页面，找到Tools\Thief-Book Config选项，选择txt文件，设置好自动翻页秒数后，重启IDEA;

4).愉快的摸鱼吧！！！！


## 未截图演示的功能:
1).阅读进度是实时保存的；

2).进度栏是可以输入的，回车跳转到输入的行数；

3).精简模式下会隐藏上下翻页按钮；

4).当你不小心将窗口关闭时，可以在WIndow菜单下选择show thief重新打开;


## 目前存在的问题：
1).设置页面的配置项必须在重启 IDEA 后才会生效；

2).点击上页按钮的速度比较慢(还没找到原因)；

3).单线程的程序，书本体积较大时，会出现卡顿；

4).精简模式下，上页翻页按钮的热键会失效；

5).热键不可以自定义(后面有空再改进)；

6).部分书本可能会出现乱码，解决方式:将书本以 utf-8 格式编码；




