###Welcome to use MarkDown
//全局安装
npm install -g webpack

//项目安装
npm install --save-dev webpack

//非全局安装指令
# {extry file}出填写入口文件的路径，本文中就是上述main.js的路径，
# {destination for bundled file}处填写打包文件的存放路径
# 填写路径的时候不用添加{}
webpack {entry file} {destination for bundled file}
webpack '文本路径' '输出路径'

//配置文件指令
webpack || npm start || npm run start

//构建本地服务器
npm install --save-dev webpack-dev-server

// npm 一次性安装多个依赖模块，模块之间用空格隔开
npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react

//安装 React 和 React-DOM
npm install --save-dev react react-dom

//安装css-loader style-loader
npm install --save-dev style-loader css-loader

//安装postcss-loader autoprefixer（自动添加前缀插件）
npm install --save-dev postcss-loader autoprefixer

//自动引用打包后的js文件新的index.html
npm install --save-dev html-webpack-plugin

//安装热加载 react-transforme-hmr
npm install --save-dev babel-plugin-react-transform react-transform-hmr

//安装分离css js文件
npm install --save-dev extract-text-webpack-plugin