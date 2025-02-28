
# 作者简介 
Mr. Zhu ，英文名aserbao! 从事Android开发多年，技术不高，用来工作刚刚好。对视频音视频处理，硬编码这一块有一定的研究。之前北漂，现在深漂。同名微信公众号aserbao的维护者，喜欢看书，摄影，交友，目前生活这样子。欢迎大家关注我的公众号和微信一起学习交流。

# 学习资料
- [Android 零基础开发相机](https://gitbook.cn/gitchat/activity/5aeb03e3af08a333483d71c1)
- [Android openGl开发详解（一） - 简单图形的基本绘制](https://www.jianshu.com/p/92d02ac80611)
- [Android openGl开发详解（二） - 通过SurfaceView，TextureView，GlSurfaceView显示相机预览（附演示）](https://www.jianshu.com/p/db8ecba6037a)
- [Android 自定义相机开发（三) —— 了解下EGL](https://www.jianshu.com/p/1e82021b10b4)

# 欢迎关注公众号领取更多openGl,相机相关学习资料
|公众号(aserbao)|个人微信号(小老头)|微信交流群|
|--|--|--|
|![](https://github.com/aserbao/AserbaosAndroid/blob/master/app/src/main/assets/images/weixin.jpg)|![](https://github.com/aserbao/AserbaosAndroid/blob/master/app/src/main/assets/images/we_chat.jpg)|![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/Android%E4%BA%A4%E6%B5%81%E7%BE%A4.jpg)|

# 项目介绍
项目目前功能有：
- 分段录制        RecorderActivity
- 多段视频合成    RecorderActivity
- 倒计时录制      RecorderActivity
- 删除回滚        RecorderActivity
- 添加滤镜        RecorderActivity
- 视频裁剪            LocalVideoActivity
- 视频方向横竖屏切换   LocalVideoActivity
- 视频旋转            LocalVideoActivity
- 视频帧处理          SelCoverTimeActivity
- 添加水印        VideoEditActivity
- 添加动态贴纸    VideoEditActivity
- 添加动态字幕    VideoEditActivity
- 文字转视频      PrimaryMediaCodecActivity

## 整体功能点效果图：
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/录制.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/摄像头切换.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/倒计时.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/回删功能.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/本地编辑.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/编辑界面.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/选封面.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/添加贴纸.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/添加字幕.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/保存到相册.gif)



## 单个功能点：
单个点主要是包括MediaCodec，AudioRecord,MediaExtractor,MediaMuxer的使用,界面效果如下：

![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/Mediacodec的基本用法.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/EncodeDecode.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/ExtractDecode.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/DecodeEditEncode.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/Mediacodec录制随音乐改变.gif)![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/MediaExtractor.gif)
![](https://github.com/aserbao/AndroidCamera/blob/master/app/src/main/assets/images/MediaMuxer.gif)


