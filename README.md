# repository（博客）

## 概述： 

- (1)这是一个利用express框架写的前端博客 
- (2)路由分为两部分：管理路由和主页路由 
- (3)服务器端为node.js模拟，数据库软件为mongodb,需要验证登录 
- (4)里面有个package.json,下载文件后，可以使用npm工具下载相应的包, 上传的文件中也上传了相应的包，命令为npm install 
- (5)在调试时建议下载全局工具nodemon,这样不用反复打开服务器，命令行为npm install nodemon -g 
- (6)验证模块joi的版本数是14.3.1，建议下载14.3.1的版本。因为最新版本的joi，运行主文件app.js时会报错，报出Joi.validate is not a function

## 个人感想： 
- (1)客户端和服务器端就是一个请求一个相应的机制，利用中间件做各种验证操作，路由就是跟你说到那个地方去 
- (2)在运行过程中，有一个明显的缺点，每次都要刷新整个网页，交户性不好，后面ajax会提高交互性，后面有待提高 
- (3)JSON.stringify(),把对象转换为字符串，后面的JSON.pares(),数据格式一定要是严格的JSON格式，不然很容易报错

## 后续想到再更新…………………………………………

## ps：第一次配置，所以仓库名就使用了repository，这个项目是一个博客

