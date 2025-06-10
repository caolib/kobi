<div align="center">
  <h1 align="center">
    <img src="lib/assets/icon.png" width="200">
    <br/>
    Kobi Comic

<a href="https://trendshift.io/repositories/10635" target="_blank"><img src="https://trendshift.io/api/badge/repositories/10635" alt="Trendshift" style="width: 200px; height: 46px;" width="250" height="46"/></a>

[![license](https://img.shields.io/github/license/niuhuan/kobi)](https://raw.githubusercontent.com/niuhuan/kobi/master/LICENSE)
[![releases](https://img.shields.io/github/v/release/niuhuan/kobi)](https://github.com/niuhuan/kobi/releases)
[![downloads](https://img.shields.io/github/downloads/niuhuan/kobi/total)](https://github.com/niuhuan/kobi/releases)

  </h1>
</div>

<br/>



一个简洁大方的漫画客户端, 同时支持 Android / iOS / MacOS / Windows / Linux.

此APP含有"吸烟/饮酒/斗殴/言情"等内容或间接性描述，限制级为R12，请在使用过程中遵守当地法律法规。

如果您觉得此软件对您有帮助，可以star进行支持。同时欢迎您issue，一起让软件变得更好。

仓库地址 https://github.com/niuhuan/kobi

[//]: # (## 预览)

[//]: # ()
[//]: # (![G01]&#40;images/G01.png&#41;)

[//]: # (![G02]&#40;images/G02.png&#41;)

## 其他

### 数据保存位置

- macos: `~/Library/Application Support/opensource/kobi`
- windows: `%CURRENT_DIR%\data`
- linux: `$HOME/.opensource/kobi`

### 本地构建

参考 Github Actions 的构建脚本

## 技术架构

客户端使用前后端分离架构, flutter作为渲染框架. rust作为底层调度网络和文件系统. Flutter与rust均为跨平台编程语言, 以此支持 android/iOS/windows/macOS 等不同操作系统.

![](https://raw.githubusercontent.com/fzyzcjy/flutter_rust_bridge/master/book/logo.png)
