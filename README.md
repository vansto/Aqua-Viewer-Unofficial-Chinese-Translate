# 请注意 这个分支是不稳定分支，可能会出现汉化错误或者是不完全汉化 且无Workflow,Github-Pages	
# 如果无特殊需求，请访问[Master分支](https://github.com/Raspberry-Monster/Aqua-Viewer-Unofficial-Chinese-Translate)	

# AquaViewer

Aqua Viewer是Aqua Server的网页UI

这个项目基于 [Angular CLI](https://github.com/angular/angular-cli) 8.3.20版本生成.

## 已部署的Master分支在线版
请访问 [![Image URL](https://aqua.raspberrymonster.top/favicon.ico)](http://aqua.raspberrymonster.top/)

请注意:如果您使用HTTPS，浏览器的安全策略可能会阻止您至游戏服务器的HTTP连接

# 获取构建

## 自动构建

### Stable分支自动构建 [![AppVeyor](https://img.shields.io/appveyor/build/RERASER/Aqua-Viewer-Unofficial-Chinese-Translate?style=flat&logo=appveyor)](https://ci.appveyor.com/project/RERASER/aqua-viewer-unofficial-chinese-translate/build/artifacts)

### Unstable分支自动构建 [![AppVeyor](https://img.shields.io/appveyor/build/RERASER/aqua-viewer-unofficial-chinese-translate-unstable)](https://ci.appveyor.com/project/RERASER/aqua-viewer-unofficial-chinese-translate-unstable/build/artifacts)	

### Stable和Unstable分支的区别
Stable（master）：Aqua Viewer更新后，由Translators翻译完成后 经过校对再同步的版本，语法错误较少但是更新慢

Unstable：Aqua Viewer更新后 立即同步，Translators翻译后立即同步的版本 更新快但是可能出现语法错误，无Github-Pages

由Aqua Viewer Translate Team进行汉化

## 从源代码进行构建
你必须安装Angular-cli然后运行 `ng build --prod`.

如果你是Angular的新手，请跟随[开发文档](https://angular.cn/guide/deployment) .


