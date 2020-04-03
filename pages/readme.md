# <font face="Adobe Garamond Pro" color=#008B8B>minium</font> {docsify-ignore}

## 简介 {docsify-ignore}
> minium


目前小程序的体量越来越大，相关的框架和组件库越来越多，对于测试能力要求也越来越高。业内同行基于[Chrome DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/)开发了很多小程序相关的测试工具，这些工具都有以下缺点：
1. 只能在Android端上运行。小程序实际是一个跨平台的产品（IDE，Android和IOS），测试的平台覆盖不足。
2. 兼容性问题。小程序底层运行的内核多样化（[x5](https://x5.tencent.com/)，原生webview内核等等），对应的调试端口不一定能够打开。
3. 只能做UI相关的测试。小程序架构上分为[渲染层和逻辑层](https://developers.weixin.qq.com/miniprogram/dev/framework/quickstart/framework.html#%E6%B8%B2%E6%9F%93%E5%B1%82%E5%92%8C%E9%80%BB%E8%BE%91%E5%B1%82)，这些框架对于逻辑层上面的测试限制较大。

而 `minium` 除了以上缺点都没有之外，还支持一下更多特性：

## 特性 {docsify-ignore}

- 支持一套脚本，iOS & Android & 模拟器，三端运行
- 提供丰富的页面跳转方式，看不到也能去得到
- 可以获取和设置小程序页面数据，让测试不止点点点
- 可以直接触发小程序元素绑定事件
- 支持往 AppSerive 注入代码片段
- 可以调用部分 wx 对象上的接口
- ...
