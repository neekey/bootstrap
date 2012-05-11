##开发日志

#### 2012-05-11

* fork Bootstrap
* 安装phantomjs
* 修改package.json里面的DevDependancies为dependancies，方便使用npm update
* **【注意】** `connect`版本使用指定的2.1.3版本，手动通过`npm install connect`安装的最新版，使用`make test`时`server.js`会出错
* 安装ruby的`watcher`模块，`make watch`命令需要用到