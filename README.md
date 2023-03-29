# RTbasic
基于rollup和TypeScript的基本仓库

## 初始化
1. npm init -y
2. 创建自己的目录

## 安装依赖
```javascript
  //ts相关包
  npm i -D typescript tslib

  //rollup相关包
  npm i -D rollup @rollup/plugin-node-resolve rollup-plugin-commonjs rollup-plugin-typescript

  //babel相关
  npm i -D @rollup/plugin-babel
  npm i -D @babel/core @babel/preset-env

```

## 添加.gitignore文件
过滤不上传到仓库的文件

## 配置TS
1. tsc --init
2. 查看ts、写入所需配置

## 配置babel
1. 创建.babelrc.json

## 配置rollup
创建rollup.config.js文件，写入对应的打包配置

