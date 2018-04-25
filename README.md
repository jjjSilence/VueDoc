# VueDoc

- npm install -g cnpm --registry=https://registry.npm.taobao.org:安装淘宝npm镜像

- npm -v:**查看版本号

- npm install npm -g:升级npm版本

- cnpm install npm -g:使用淘宝镜像升级npm版本

- npm install:下载node_modules


- npm run xxx:执行配置在package.json中的脚本,只有这里配置了才能run,比如下面的可以执行npm run dev

<pre>
  "scripts": {
    "dev": "webpack-dev-server --inline --progress --config build/webpack.dev.conf.js",
    "start": "npm run dev",
    "build": "node build/build.js"
  },
</pre>


- cls：清理控制台

- ctrl+c：停止连接

- axios：[网络请求的http库](https://segmentfault.com/a/1190000014413601)

- webpack -v:安装webpack,需要全局安装和

- [notepad连接服务器](https://jingyan.baidu.com/article/48a42057eeb1a5a9242504a3.html)

- npm install webpack --save-dev:开发时依赖的东西

- npm install webpack --save:开发后要需要依赖的东西
