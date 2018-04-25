# VueDoc

### vue项目的环境要求

##### 1、 安装npm淘宝镜像，升级npm

- npm install -g cnpm --registry=https://registry.npm.taobao.org:安装淘宝npm镜像

- npm -v: 查看版本号,检查npm是否安装成功

- npm install npm -g:升级npm版本, -g表示全局

- cnpm install npm -g:使用淘宝镜像升级npm版本

##### 2、安装webpack
- npm install webpack -g:全局安装webpack

- npm install webpack --save-dev:开发时依赖的东西

- npm install webpack --save:开发后要需要依赖的东西

- webpack -v:检查是否安装成功

##### 3、安装vue脚手架

- npm install vue-cli -g


### 新建vue项目

##### 1、新建文件夹webapp来保存所有vueApps项目, 在终端进入该目录：
- 'f:' : 进入f盘
- 'cd xxx': 切换到那个文件下，直接将目标文件拖到终端即可

##### 2、创建项目
- vue init webpack projectName：创建完成后 projectName 的文件夹下多出很多文件

##### 3、进入项目，下载依赖
- npm install 或者 cnpm install：找到当前路径下的package.json,安装其中的依赖

##### 4、运行项目
- npm run dev

- npm run xxx:执行配置在package.json中的脚本,只有这里配置了才能run,比如下面的可以执行npm run dev,npm run build

<pre>
  "scripts": {
    "dev": "webpack-dev-server --inline --progress --config build/webpack.dev.conf.js",
    "start": "npm run dev",
    "build": "node build/build.js"
  },
</pre>

##### 5、停止运行

- ctrl+c：停止连接

- cls：清理控制台

- [notepad连接服务器](https://jingyan.baidu.com/article/48a42057eeb1a5a9242504a3.html)

### axios请求
- axios：[网络请求的http库](https://segmentfault.com/a/1190000014413601)


