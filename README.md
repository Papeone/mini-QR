# mini-QR
快记小程序

## 环境

1. 全局安装 chameleon-tool 构建工具
```
npm i -g chameleon-tool
```
安装成功后，执行 cml -v 即可查看当前版本， cml -h查看命令行帮助文档

2. 下载项目依赖
```
npm install
```

## 启动项目
```
cml dev
```

## 项目预览
使用chameleon playground Android端App预览。下载地址：[download](https://cmljs.org/playground/download.html)


## 目录与文件结构
```
├── chameleon.config.js                 // 项目的配置文件
├── dist                                // 打包产出目录
  ├── alipay                            // 支付宝小程序代码
  ├── baidu                             // 百度小程序代码
  ├── wx                                // 微信小程序代码
  ├── tt                                // 头条小程序代码
  ├── qq                                // QQ小程序代码
  ├── xx                                // 其他终端
├── mock                                // 模拟数据目录
├── node_modules                        // npm包依赖
├── package.json
└── src                                 // 项目源代码
    ├── app                             // app启动入口
    ├── components                      // 组件文件夹
    ├── pages                           // 页面文件夹
    ├── router.config.json              // 路由配置
    └── store                           // 全局状态管理
```    
## 创建新页面

项目根目录下  执行 cml init page, 输入页面名称
```
cml init pageName
```

## 创建组件

项目根目录下  执行 cml init component

## 项目配置

chameleon.config.js为项目的配置文件，以后定制化构建会  使用到，比如是否带 hash，是否  压缩等等,可以在项目根目录下执行cml build ， 执行完成后 ，项目根目录的dist文件夹下生成 build 模式的文件。

## 编辑器推荐及插件安装

推荐使用vscode 插件搜索 cml 安装。

