# 目录结构

```
│  package.json                      // npm包管理所需模块及配置信息
│  vue.config.js                     // webpack配置
├─public
│      favicon.ico                   // 图标
│      index.html                    // 入口html文件
└─src
    │  App.vue                       // 根组件
    │  main.js                       // 程序入口文件
    ├─assets                         // 存放公共图片文件夹
    ├─components
    │      Footer.vue                // 页面底部公用组件
    │      Header.vue                // 页面头部公用组件
    ├─router
    │      index.js                  // 单页面路由注册组件
    ├─store
    │  │  index.js                   // 状态管理仓库入口文件
    │  └─modules
    │          userInfo.js           // 用户模块状态管理文件
    ├─styles
    │      base.scss                 // 基础样式文件
    ├─utils
    │      api.js                    // 统一封装API接口调用方法
    │      network.js                // axios封装与拦截器配置
    │      url.js                    // 自动部署服务器环境
    │      valid.js                  // 统一封装公用模块方法
    └─views
            Home.vue                 // 首页界面
            Login.vue                // 登录界面
```

# 技术栈

- vue2.6
- axios
- webpack
- ES6/7
- flex
- iViewUI

# 功能模块

- 登录（登出）
- 注册
- 记住密码
- 忘记密码（修改密码）
- todo 增删改查
- 点亮红星标记
- 查询条件筛选

# 下载安装依赖

```
git clone https://github.com/jackchen0120/todo-vue-admin.git
cd todo-vue-admin
npm install 或 yarn
```

## 开发模式

```
npm run serve
```

运行之后，访问地址：http://localhost:8082

## 生产环境打包

```
npm run build
```
