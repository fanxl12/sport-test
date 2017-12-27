# sport-test

> 测试项目

## 运行步骤

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev
```

本项目通过vue-cli搭建出一个空的元素项目, 应聘者需要在此基础上实现一个瀑布流功能。
要求如下：
1. 项目为移动端项目，实现在移动端展现的效果;
2. 瀑布流为两列显示;
3. 瀑布流图片需要按照a-o的顺序展现;
4. 支持下拉刷新和上拉加载，下拉刷新模拟网络请求，显示原始的a-o15张图片;
5. 上拉加载，需要模拟网络请求的过程(显示正在加载中提示)，再加载a-o15张图片，且顺序不能错乱；
6. 上拉加载超过90张，底部显示全部加载完毕样式，不能再继续上拉加载了；
7. 大概样式和元素可以参考原型图，单需要进行UI上的调整和设计;

>图片素材在src/assets/images下面, 项目完成之后发到此邮箱 fanxiaole@highyundong.com

## 参考原型图

![原型图](src/assets/01.jpg)