# dva

[dva](https://github.com/dvajs/dva) 是一个基于 React 和 Redux 的轻量应用框架，概念来自 elm，支持 side effects、热替换、动态加载、react-native、SSR 等。

## 安装

安装 [cnpm](https://www.npmjs.com/package/cnpm)

```bash
$ npm install cnpm -g --registry=https://registry.npm.taobao.org
```

安装 [dva-cli](https://github.com/dvajs/dva-cli)，确保版本是 `0.9.1` 或以上。

```bash
$ cnpm install dva-cli -g
```

## 新建项目

安装完 dva-cli 之后，就可以在命令行里访问到 `dva` 命令。现在可以通过 `dva new` 创建新应用。

```bash
$ dva new react-dva-samples
```

工具会创建 `react-dva-samples` 目录，包含项目初始化目录和文件，并提供开发服务器、构建脚本、数据 mock 服务、代理服务器等功能。

## 初始化项目

`cd` 进入 `react-dva-samples` 目录，安装依赖。

```bash
$ cd react-dva-samples
$ cnpm install
```

## 启动

`cd` 进入 `react-dva-samples` 目录，并启动开发服务器。

```bash
$ cd react-dva-samples
$ cnpm start
```

几秒钟后，你会看到以下输出：

```bash
Compiled successfully!

The app is running at:

  http://localhost:8000/

Note that the development build is not optimized.
To create a production build, use npm run build.
```

此时浏览器会访问 http://localhost:8000 ，看到 dva 的欢迎界面。
