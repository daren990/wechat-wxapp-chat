##BUG

- 微信越来越傻帽了, 微信小程序socket就是接收不到值(而且造成服务器ws模块各种问题, 要使调试环境的微信小程序请求nodejs时, nodejs不报错, 必须设置 `verifyClient: socketVerify`),用原生的 websocket(client文件夹下)不知多么正常,无语了...

- 预览时居然不会编译es6原有的方法 `Object.assign` 等, 所以在手机上是个大坑(还是得用我强大的babel来救场)...