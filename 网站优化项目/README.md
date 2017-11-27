# 网站优化项目QA
> 这个部分将讲解网站优化项目部分的QA

## 准备工作
### 开始设置
* 手机端：需要打开手机USB调试功能。首先你需要将手机设备调到开发者模式，一般的方法是打开设置选项，找到关于手机/设备，点击版本号七次，接下来你就可以在开发者选项中打开USB调试模式了。
* 开发设备：在电脑端安装[Chrome Canary](https://www.google.com/chrome/browser/canary.html) ,当然，chrome也是可以的。手机端安装chrome即可。

### 使用
* 在开发者设备上打开chrome的inspect页面
* 在手机端打开需要调试的网页，使用USB线连接设备
* 然后手机端确认允许使用USB调试，此时开发设备将会显示已连接设备的列表以及设备上的chrome标签
* 我们可以在开发设备上面打开其他的网页，进行刷新、切换、关闭等等操作
* 以上操作开发设备进行时手机设备都将同步进行
* 可以点击`inspect`来检视移动端设备打开的页面
* 使用屏幕投映模式在开发设备上体验手机端
* 对于IOS移动端用户可以查看：
	* [iOS WebKit 调试代理](https://github.com/google/ios-webkit-debug-proxy)
	* [Testing Mobile: Emulators, Simulators And Remote Debugging](https://www.smashingmagazine.com/2014/09/testing-mobile-emulators-simulators-remote-debugging/2/)

### 参考资料
* [在装有 Chrome 的 Android 上远程调试](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/?hl=zh) | [国内翻译文档](http://www.css88.com/doc/chrome-devtools/remote-debugging/)
* [远程调试安卓设备](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/) | [国内翻译文档](http://www.css88.com/doc/chrome-devtools/remote-debugging/)

## 关键渲染路径
### 使用 Google 的 [Web Fundamentals](https://developers.google.com/web/fundamentals/) 手册详细了解[关键渲染路径](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)。基本上你需要的概念知识这里都有
