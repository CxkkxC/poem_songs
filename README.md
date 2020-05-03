## 博客地址

https://blog.csdn.net/Cxk___/article/details/105908482

## 视频预览
[video(video-Irox5VaA-1588510066407)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=795543097)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/b3d15f18375c5c1a205b9faea9bd3f3fe20d36d9.jpg)(title-诗音情)]https://www.bilibili.com/video/BV1DC4y1W7WS/https://www.bilibili.com/video/BV1DC4y1W7WS/
## 吐槽
如题所示，贼难受，就好像幸幸苦苦追了一星期的女孩突然对自己说：对不起，我有男票了！不过问题不大，一开始就没好好阅读小程序规矩，怪不了谁。毕竟在人家地盘，就该遵守人家的规矩。
	
但是花时间心血做的不能这样白白浪费了，毕竟这是好东西啊，对于我们菜鸟来说，练手必备。所以这里分享给大家学习使用吧！
![各版本目录](https://img-blog.csdnimg.cn/20200503210405443.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0N4a19fXw==,size_16,color_FFFFFF,t_70#pic_center)至于毙的原因呢我这里也说一下吧，我是个人版小程序，不能发布带有社交内容的东西，但是一开始就奔着用户原创内容去的，叫我将这模块毙了那这小程序没啥意义了。所以这里就不打算改了，开源供大家学习使用，至于后台服务器端我将一直开放着，有需要的同学也可以叫我将后台源码给你。
## 整体架构
![项目目录](https://img-blog.csdnimg.cn/20200503210538875.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0N4a19fXw==,size_16,color_FFFFFF,t_70#pic_center)
其中dist文件是使用了vant框架的部分组件，我这里使用的是直接调用源码，不需要再npm了。
images是静态图片图标，pages是各个页面。
![页面目录](https://img-blog.csdnimg.cn/2020050321075611.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0N4a19fXw==,size_16,color_FFFFFF,t_70#pic_center)

 - about--关于页面
 - audiolist--用户个人录音页面
 - poeminfo--录音界面
 - poemlist--用户原创分享页面
 - poempeople--用户主页
 - poemshow--用户语音跟原创展示页
 - poemsong--搜索诗数据库主页
 
