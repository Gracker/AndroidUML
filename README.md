# AndroidUML
此项目是一个Android UML图的集合，以前大家画UML图的时候，是使用画图工具来进行绘图的，这样一旦完成之后，别人来修改的代价
就很高，自己去修改的动力也不大，更不利于修改和传播。
而程序员更喜欢用代码或者伪代码来进行写作，PlantUML就是使用简单的语法来绘制各种UML图，非常方便，也易于修改，简直是程序员福音。

# PlantUML
所以此项目中的UML使用的是[PlantUML](http://www.plantuml.com/sequence.html)工具，这个工具有独立的版本，也有很多IDE的插件，使用起来比较无脑，教程的话，看官方教程即可。
也有中文版的。所以使用方法这里就不进行介绍了。

# 关于此项目
1. 此项目所有的UML图都是使用PlantUML工具完成的，其源码大家都可以看到，拷贝到项目中（带PlantUML插件的IDE）就可以看到图片，方便大家进行修改和收藏。
2. 此项目中的所有 UML 图都是 Android 相关的图，这样对于Android开发者来说是一个提高自己，并且记录自己学习过程的好方法，好记性不如烂笔头，千行文字不如一张图，讲的就是这个道理。
3. 此项目中所有的 UML 图都应该保证是正确的，不要误导别人，每一张图都要标明自己的版本号和Android平台的版本号。

# 参与
欢迎大家fork和提交PR，将自己的知识共享出来，大家共同进步

# 联系
weibo ： [高爷](http://weibo.com/gracker520?is_all=1)  
qq : 553000664

# 目前已经存在的UML图及其预览

1. Android HWUI : Sync Between UI And Render Thread

    ![Android HWUI : Sync Between UI And Render Thread](/hwui/SyncBetweenUIAndRenderThread.png)

    下面这张图是一个简单的分析，Android的HWUI是如何在绘制之前同步主线程的数据到RenderThread的：   
    ![Android HWUI Analysis : Sync Between UI And Render Thread](/hwui/SyncBetweenUIAndRenderThread_Analysis.png)
