# React CLI

<p text-align="center">
    <img alt="react" src="https://img.shields.io/badge/react-16.8.2-brightgreen.svg?style=for-the-badge"/>
    <img alt="react--router" src ="https://img.shields.io/badge/react--router-4.3.1-blue.svg?style=for-the-badge"/>
    <img alt="react--router" src ="https://img.shields.io/badge/react--router--config-4.4.0--beta.6-critical.svg?style=for-the-badge"/>
    <img alt="redux" src ="https://img.shields.io/badge/redux-4.0.1-ff69b4.svg?style=for-the-badge"/>
    <img alt="react--responsive" src ="https://img.shields.io/badge/sass--loader-7.1.0-blueviolet.svg?style=for-the-badge"/>
</p>

初版react脚手架

### 1.工程特点

- 已默认添加ant-design的UI框架
- 已配置sass预处理
- 使用@符号定位src资源目录
- 集成redux及其使用demo
- react-router + react-router-config 实现路由统一配置以及按需加载
- 封装fetch请求



### 2.目录说明

已使用 npm run eject 暴露配置文件

```
├─config    //默认配置文件夹
├─public    //公共文件
│      favicon.ico
│      index.html
│      manifest.json
│      
├─scripts   //node命令
│      build.js
│      start.js
│      test.js
│      
└─src      //资源文件
    │  App.js
    │  App.test.js
    │  index.js
    │  logo.svg
    │  serviceWorker.js
    │  
    ├─api   //接口配置文件
    │      index.js
    │      
    ├─assets  //静态资源
    │  ├─css
    │  │      App.scss
    │  │      index.css
    │  │      
    │  └─images
    ├─components  //组件
    │      main.js
    │      
    ├─config  //各种其他配置
    │  │  index.js
    │  │  
    │  └─fetch  //封装fetch配置文件夹
    │          config.js
    │          index.js
    │          
    ├─router   //路由文件夹
    │      bundle.js
    │      index.js //合并导出所有路由
    │      router.js //拆分后的路由文件
    │      
    ├─store  //redux文件夹
    │  │  index.js //合并reducers
    │  │  
    │  ├─actions //actions文件夹
    │  │      index.js 
    │  │      nav.js //对应拆分后的actions
    │  │      
    │  └─reducers  //拆分后的reducers
    │          nav_reducer.js
    │          
    └─utils  //工具文件夹
```



### 3.路由配置





### 4.调用请求



