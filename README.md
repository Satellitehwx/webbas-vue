# webbas-vue

### 确保开发机器成功安装node和npm后 执行以下操作创建项目

### npm是nodejs的包管理工具，为了加快下载速度，可安装淘宝镜像，安装成功后可cnpm代替npm，在终端输入

```npm install -g cnpm --registry=https://registry.npm.taobao.org```

### 全局安装vue-cli，在终端输入

```npm install -g vue-cli / cnpm i -g vue-cli```

### 安装成功后，可用 vue -V 查看vue版本。

### 使用脚手架创建项目

```vue init webpack "webbas-vue"```

webbas-vue为项目名称

```
AppledeMacBook-Pro-3:~ apple$ vue init webpack vue-demo
? Project name vue-demo        //（工程名）:回车
? Project description A Vue.js project    // （工程介绍）：回车
? Author crr     // (作者名)：作者名
? Vue build standalone        // （是否安装编译器）:回车
? Install vue-router? Yes      // （是否安装Vue路由）：回车
? Use ESLint to lint your code? No     //（是否使用ESLint检查js代码）：n
? Set up unit tests No       //（安装单元测试工具）：n
? Setup e2e tests with Nightwatch? No     //（是否安装端到端测试工具）：n
? Should we run `npm install` for you after the project has been created? (recom
mended) npm              //  (recommended)：回车
```

### 启动项目

```npm run dev```
