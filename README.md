# 注意点
- hash:特定于整个构建过程的
- chunkhash：特定于每个文件内容的
- 一行代码理解：loader : function(content) { return newContent}
- 如果修改的是css文件，则会局部刷新，如果修改的是客户端的js文件，则浏览器整页会刷新，如果修改的是后台代码，则后台服务器会重启，再刷新前端整页
- webpack-dev-server本质上是一个静态资源服务器
- webpack-dev-middleware和webpack-hot-middleware的静态资源服务只用于开发环境。到了线上环境，应该使用express.static()。

[参考手册](https://doc.webpack-china.org/configuration)
