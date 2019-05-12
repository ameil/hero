# hero

> A Vue.js project

## Build Setup

``` bash

npm install -g cnpm --registry=https://registry.npm.taobao.org    //全局安装（全局能用的话这步省略）

npm install -g vue-cli 

vue init webpack-simple hero

cd hero 
# install dependencies 
npm install --cache-min 99999999  //从内存中下载依赖 速度较快
npm install //重新从网络下载依赖

# serve with hot reload at localhost:8080 
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
