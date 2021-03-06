# 404-Blog
## Express 学习

Express 是一个基于 Node.js 平台的极简、灵活的 web 应用开发框架，它提供一系列强大的特性，帮助创建各种 Web 和移动设备应用。

***

#### 安装环境
```
$ cnpm install express-generator -g
```
#### 创建应用
```
$ express APP_NAME
```
#### 安装依赖包
```
$ cd myapp 
$ cnpm install
```
#### 启动

MacOS / Linux :
```
$ DEBUG=myapp npm start
```
Windows :
```
> set DEBUG=myapp & npm start
```
#### 查看
[http://localhost:3000/](http://localhost:3000/)

***

#### 结构

app.js为入口，包括顶级路由。
routes文件夹下放次级路由。
views文件夹下放页面文件，jade格式，支持block。

Express 定义了如下和 HTTP 请求对应的路由方法：
* get
* post
* put
* head
* delete
* options
* trace
* copy
* lock
* mkcol
* move
* purge
* propfind
* proppatch
* unlock
* report
* mkactivity
* checkout
* merge
* m-search
* notify
* subscribe
* unsubscribe
* patch
* search
* connect

*其他部分在实践中慢慢练习。*
