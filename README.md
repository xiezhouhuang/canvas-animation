# canvas-animation

  canvas实现逐帧动画效果

## pxloader-images.min.js
  
  图片加载库

## http://res.wx.qq.com/open/js/jweixin-1.0.0.js
  
  微信JS-SDK
 
### 说明

1.index.html 必须在微信端开启

2.考虑到动图与音频的同步播放,setInterval 的播放间隔可以自动调节

3.注释clearInterval,可以让图片循环播放,必须考虑音频同步

4.weixin-demo.html 利用了微信播放图片方式 支持WEB端 可以自己加音频