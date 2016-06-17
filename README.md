#基于vue.js重写qjzd.net社区的webapp [线上访问地址](http://vue.qjzd.net)

###安装

项目地址：（`git clone`）

```shell
git clone https://github.com/nqdy666/Qjzd-vue
```

通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install
```
启动服务(http://localhost:8080)

```
npm start
```
发布代码
```
npm run deploy
```

###开发

###目录结构
<pre>
.
├── README.md
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // css js 和图片资源
│   ├── components     // 各种组件
│   ├── views          // 各种页面
│   ├── filters.js     // 各种过滤器
│   └── main.js        // Webpack 预编译入口
├── server.js          // webpack-dev-server服务配置
├── gulpfile.js        // gulp 配置文件
├── disk2gh-pages.sh   // 把disk的内容发布到gh-pages分支
└── webpack.config.js  // Webpack 配置文件
</pre>

