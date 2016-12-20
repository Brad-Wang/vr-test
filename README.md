# 初探框架VRview for web

> VRview是google研发的一款用于VR播放的框架，这次咱们一起好好了解一下VRview for web，就是这个框架的前端版本。在这里也附上VRview的官网地址：。
本文所讲主要是将笔者的使用框架时的一些体会和感触，整理出来。
请大家看我的一个demo，地址：

### 基本使用——创建我的第一个demo
按照官网上的说法，使用起来似乎非常简单，弄个demo不就是分分钟的事吗~
可是，可是，略微有点坑。

##### 1.引入VRview的js文件

官网的说法是，让你引入：
`<script src="//storage.googleapis.com/vrview/2.0/build/vrview.min.js"></script>`
你可以用浏览器直接打开src属性的地址，看下js源码。
由于这个网址在墙外，未来方便及性能考虑，复制了源码，放在了本地。
