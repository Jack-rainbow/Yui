# Yui

[![Build Status](https://travis-ci.com/jack-rainbow/Yui.svg?branch=master)](https://travis-ci.com/jack-rainbow/Yui)
[![NPM License](https://badgen.net/npm/license/@femessage/el-data-table)](https://github.com/jack-rainbow/raw/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/jack-rainbow/pulls)


## 介绍

整合组件 :fire:


## Features

- [x] 代码打包 📦 npm lib 即可
- [x] 代码即文档，代码里面加注释即可解决文档问题
- [x] `yarn new` 交互式创建新组件文件，不用再繁琐的写 `template`
- [ ] 添加 jsx
- [ ] 添加实时编译
- [ ] 添加 自动引入css
- [ ] 添加 自动引入js文件
- [ ] standard-version
- [ ] 自动生成 release logs

## Project setup

由于 `vuepress` 依赖的是 `core-js` 是 2.x 版本，而 `vue-cli3` 中依赖的是 3.x 版本.

所以 `vuepress` 需要进行全局安装。

```js

npm i -g vuepress core-js@2.6.11

```

```
git clone 

yarn install

yarn docs:dev // 启动开发模式

yarn new // 创建新组件
```

## 发布

在整合..

```shell
yarn pub

# 更新 package.json 然后

npm publish
"pub": "yarn build:lib && yarn build:theme",
```

### 参考链接
- https://github.com/vue-styleguidist/vuepress-plugin-live
- https://github.com/BuptStEve/markdown-it-vuese
- https://github.com/shuidi-fed/vuese
- https://markdown-it.github.io/markdown-it/
- https://github.com/koca/vue-prism-editor
- https://juejin.im/post/5dd234635188254a1f44646a#heading-27
- https://segmentfault.com/a/1190000015261753



## 扩展 ✨

1.vuepress实时编译vue文件插件vuepress-plugin-live