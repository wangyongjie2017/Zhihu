﻿# 知乎日报

## 声明
api来自知乎( [知乎Zhihu](http://www.zhihu.com/) ), 项目中所有内容的一切权利属于知乎, 本项目所有内容及代码仅供私下学习参考, 不得作为其他用途

## 简介
- 学习Vue.js蛮久的了, 也看了不少别人写的知乎日报, 干脆自己也拿日报练练手, 该项目使用vue-cli构建、打包, 配合vue全家桶（vue、vuex、vue-router）进行编码、使用axios进行资源请求


- 图片防盗链问题使用以下meta标签解决。http协议中如果从一个网页跳到另一个网页，http头字段里面会带个referer，图片服务器通过检测referer是否来自规定域名，来进行防盗链。如果没有referer，服务器会认为是浏览器直接打开了文件，所以可以正常显示。

  ``` bash
  <meta name="referrer" content="never">
  ```
- 欢迎issue、fork、star😁



## 运行方法

``` bash
npm install
npm run dev

```
