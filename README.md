<p align="center"><img src="./hapv.png" alt="hapv"></p>

electron 开发的一个可以播放,下载国内主流视频的播放器。A player developed by electron that can play and download domestic mainstream video.

## 下载

- [下载体验](https://gitee.com/meetqy/hapv/releases)

## 界面

|            \*\*\*            |            \*\*\*            |
| :--------------------------: | :--------------------------: |
| <img src='./preview/1.png' > | <img src='./preview/4.png' > |
| <img src='./preview/2.png' > | <img src='./preview/3.png' > |

## 技术栈&插件

- Electron
- Vue
- vue-cli-plugin-electron-builder
- Element

下载功能需安装 [annie](https://github.com/iawia002/annie)

## 如何运行

```
git clone git@github.com:meetqy/hapv.git
```

```
cd hapv
```

```
npm install
```

```
npm start
```

## 原理

1. 利用`electron`框架，返回 web 页面
2. 页面中嵌入 webview，url 为各平台官网
3. 利用`electron`提供的 api，监听页面跳转，劫持链接，返回解析之后的视频链接。

## 开发规范

- [开发规范](./开发规范.md)

## 版本记录

- [版本记录](./版本记录.md)
