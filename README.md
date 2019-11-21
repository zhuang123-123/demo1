#  vue2-echo
    自己尝试学习git提交

## 技术栈
1. [vue](https://cn.vuejs.org/v2/guide/)、 [vue-router](https://router.vuejs.org/zh-cn/essentials/getting-started.html)、 [vuex](https://vuex.vuejs.org/zh-cn/getting-started.html)
2. [axios（请求库）](https://github.com/axios/axios)
3. [mint-ui（饿了么移动端UI库）](http://mint-ui.github.io/docs/#/zh-cn2)
4. [vue-progressbar（加载进度条）](https://github.com/hilongjw/vue-progressbar)
5. [amfe-flexible（淘宝适配库）](https://github.com/amfe/lib-flexible)
6. [mockjs（数据模拟）](http://mockjs.com/)
7. [ES6/7（JS语法）](https://github.com/lukehoban/es6features)、[ESlint（JS语法规范）](https://github.com/standard/standard/blob/master/docs/RULES-zhcn.md)
8. [Stylus（css预处理器）](https://github.com/stylus/stylus)
9. [IconFont（阿里字体库）](http://www.iconfont.cn/)

## 目录结构

``` bash
├── src                          
│   ├── api                      // 请求api
│   ├── assets                   // 静态资源
│   ├── components               // 全局组件
│   ├── filters                  // 全局过滤
│   ├── mock                     // 模拟数据
│   ├── page                   
│   |   ├── detail               // 详情页
│   |   ├── index                // 首页
│   ├── router                   // 路由
│   ├── store                    // 状态管理
│   ├── utils                    // 公用方法
│   ├── App.vue
│   └── main.js
├── .env.development             // 开发环境变量
├── .env.production              // 生产环境变量
├── package.json                 // 项目依赖
└── vue.config.js                // vue-cli 3.0配置
```

## 开发和发布

``` bash
# 安装依赖
npm install

# 启动项目：localhost:8001
npm run dev

# 打包项目
npm run build

# 查看构建报告：/dist/report.html
npm run build:report
```
