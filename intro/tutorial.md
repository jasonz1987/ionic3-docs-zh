## Ionic 向导

完成了[ionic及其依赖的安装](/intro/installation.md)后，让我们开始编译你的第一个app吧。这一节我们将手把手指导你完成创建一个新的应用，添加页面，页面间跳转以及其他内容，让我们开始吧！

> Ionic使用TypeScript进行编码。你不用太担心，即使你不熟悉他，他和常规的javascript其实很相似。当然，如果想深入了解以下，可以看一下[开发资源这一页](/resources.md)。

### 创建一个新的App

创建App前，请打开终端/命令行并且运行以下命令

```
$ ionic start MyIonicProject tutorial
```

* `start` 让CLI创建一个新的app
* `MyIonicProject`是你项目的app名称以及创建的目录名称
* `tutorial`表示你项目使用的初始化模板 

除了创建项目之外，也同时会安装应用对应的[node modules](/resources.md)，以及提示你是否安装[Cordova](/resources.md).

除了tutorial模板外，Ionic也提供了这些官方模板

* `tabs`: 一个简单的3tab模板
* `sidemenu`: 一个带有侧边滑动菜单的布局
* `blank`: 一个单页的空白启动项目
* `super`: 超过14可用的页面设计的启动项目
* `tutorial`: 一个向导的启动项目

如果你刚开始没有指定模板，系统将会提示选择一个模板。

### 在浏览器里浏览App

现在你可以使用`cd`命令进入你创建的目录。为了可以在浏览器中得到快速的预览，你可以使用`serve`命令

`$ cd MyIonicProject/`

`$ ionic serve`

![](/assets/tutorial-screen.png)

在下一节，让我们分析以下通过`ionic start`命令创建的目录结构

