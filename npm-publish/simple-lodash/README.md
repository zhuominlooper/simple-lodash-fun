## **simple-lodash-fun**

![Build Status](https://travis-ci.org/wulv/del-expired-file.png)
![npm version](https://img.shields.io/npm/v/simple-lodash-fun.svg?style=flat-square)
![npm downloads](https://img.shields.io/npm/dm/simple-lodash-fun.svg?style=flat-square)
![gitter chat](https://img.shields.io/gitter/room/mzabriskie/simple-lodash-fun.svg?style=flat-square)
![code coverage](https://img.shields.io/coveralls/mzabriskie/simple-lodash-fun.svg?style=flat-square)

---

## **NPM Installation**

- 全局安装:npm i -g simple-lodash-fun
- 本地安装:npm i simple-lodash-fun -D
- 产线安装:npm i simple-lodash-fun -S

---

## **CDN Installation**

```javascript
<script src="https://cdn.jsdelivr.net/npm/simple-lodash-fun/dist/index.umd.js"></script>
```

---

## **Current Function**

| 函数名称        |         函数作用 | 是否测试通过 | 创建时间  |
| --------------- | ---------------: | -----------: | :-------: |
| accurateType    | 准确判断数据类型 |          YES | 2021/7/10 |
| pseudoArr2Array |   伪数组转真数组 |          YES | 2021/7/10 |
| deepClone       |           深拷贝 |          YES | 2021/7/12 |

---

## **Browser Support**

| ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Latest ✔                                                                                 | Latest ✔                                                                                    | Latest ✔                                                                                 | Latest ✔                                                                              | Latest ✔                                                                           | 11 ✔                                                                                                                         |

[![Browser Matrix](https://saucelabs.com/open_sauce/build_matrix/axios.svg)](https://saucelabs.com/u/axios)

---

## **Example**

```javascript
nodeJs：
const fun = require("simple-lodash-fun");
console.log(fun.accurateType(null)); //Null
console.log(fun.accurateType([])); //Array
```

```javascript
ES6：
import * as _ from "simple-lodash-fun";
console.log(_.accurateType(null)); //Null
console.log(_.accurateType([])); //Array
```

---

## **License**

### MIT

---

## **Npm DevDependents**

```javascript
@babel/cli
@babel/core
@babel/preset-env
babel-loader
chai
cross-env
eslint
eslint-config-airbnb-basees
lint-plugin-import
jest
mocha
mochawesome
webpack
webpack-cli
nyc
```

---

## **Engineering**

## <img src="https://user-gold-cdn.xitu.io/2018/5/13/163583bef8f07f05?imageView2/0/w/1280/h/960/format/webp/ignore-error/1" width=556 height=256 />

---

## **Versions**

```javascript
v-1.1.1(2021/7/12)
tag:添加了几个常用函数并测试,添加cdn包

v-1.1.0(2021/7/10)
tag:初始化webpack,test工具,搭建好环境并上传到npm

v-1.0.0(2021/7/10)
tag:初始化包


```

---