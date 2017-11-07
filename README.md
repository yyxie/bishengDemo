## 抽离antd中必须用的内容，做一个自己的react组件API管理

## 使用方式
npm install
npm run bisheng

## 学习bisheng 的辛苦历程（主要是因为自己比较low ,😂）
* 当时就想要做个api文档管理，最开始在网上搜看到vue的api脚手架 docute挺好用的，就尝试用了下，结果发现是能用来编译md文档，使用起来也挺方便。但是老大给我的需求是需要再md文件中书写reat实例。这就有点难度发现使用docute好像是解决不了这个需求
* 上面条路走不通，经老大的提醒说可以看下🐜的api是怎么实现，经过一番倒通找到了bisheng,但是资料实在是太少了，只能多翻看别人的使用实例。费了九牛二虎之力终于实现了这个API文档

## 如何使用bisheng PS: 这里面我将英文部分给删除了
* 编译的配置文件是在 site/bisheng.config.js
>  port: 服务监听的端口号
>  components: API放置的位置
>  docs: 介绍文档放置的位置
>  theme: 文档主题，可以修改成自己喜欢的，或者用bisheng中原有的
>  htmlTemplate: './site/theme/static/template.html',
* 路由的一些配置是在 site/theme/index.js
* 中文菜单配置 site/theme/zh-CN.js


