# WX-bilibili-Demo

**由于接口的视频资源域名失效，所以点击进视频页后有加载不出来的情况**

# 新人一定要看使用须知,一定要看使用须知,一定要看使用须知,重要的事情要说三遍

## 使用须知及Q&A

## **如何解决视频中的font-awesome问题**
- 使用CSS转wxss功能将整个font-awesome的文件打包成wxss格式(只使用两个图标但导入整个库有点不划算)
- 使用SVG文件的图标,再通过阿里巴巴icon的项目下载功能打包到本地成为字体文件(有点麻烦)
- 使用png图像,并使用image标签代替视频中的i标签或view标签(推荐,记得在wxss中限制大小)
- 使用base64压缩功能将小图片文件转换为base64格式并使用image标签代替i标签或view标签引入(个人使用,优点是不用多放几张图,缺点是会增加wxml的大小以及降低代码可读性)

### 如何引入到自己的项目中使用
- 使用命令行,在命令行中输入以下命令将项目Clone至本机中,在微信开发者工具中导入项目即可
  > git clone https://github.com/q867304130/WX-Demo-bilibili.git

- 点击项目右上角的 Clone or download ,选择 Download ZIP ,将文件下载到本地中,解压缩后使用微信开发者工具导入

### 如何在自己的手机上测试
没有任何文章比官方文档更权威了:https://developers.weixin.qq.com/miniprogram/dev/

### 为什么接口数据非常缓慢
接口速度取决于你的网络速度,这个和接口服务器有关

### 为什么视频链接只能点开4个
可能是为了节省流量(?)吧,接口的视频链接那已经只能读取出4个了

### 怎么把这个小程序上线?
微信小程序的审核麻烦得要死(3分钟内连续拿出5次手机扫码),我已经放弃了,如果你有兴趣和耐心的话可以试试
