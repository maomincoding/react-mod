# react-mod

React企业级项目模板，即插即用。

 **一、** UI框架使用的是 [Ant Design of React](https://ant.design/docs/react/introduce-cn) ,你可以登录官网按需引入。

 **二、** 预装了很多依赖，如果不需要可以在全局安装依赖时，在`package.json`中删除对应的依赖就可。一般默认的这些依赖都是项目需要用到的。

 **三、** 需要注意的是，安装的`react-loadable` 会提示`componentWillMount has been renamed`的warning。如果想消除警告，可以在目录`node_modules/react-loadable/lib/index.js`中的`componentWillMount`改为
 `UNSAFE_componentWillMount`，就可以消除了。

 **四、** 目录`public/api`下的文件是本地模拟数据用的，如果不需要可以删除，需要注意其他页面或许调用这些接口

 **五、** 目录`src/request/` 这两个只是基本配置，如果想进行升级的可以查看这篇文章[三次封装axios](https://juejin.im/post/5e94306bf265da47d4057448) ,虽然是Vue的，思路是一样的。


