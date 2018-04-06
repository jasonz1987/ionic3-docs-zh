## 安装ionic

ionic应用主要是使用ionic命令行（简称CLI）创建和开发，并最终通过\`Cordova\`编译/部署成为原生APP。因此在开发前我们需要安装一些组件。

### 安装Node和NPM

CLI中的大部分组件都是依赖于Node并且通过NPM进行管理的。安装Node和Npm最简便的方法是使用[NodeJS installer](https://nodejs.org/)。为了确保能够安装到Node的LTS版本，在安装前请关闭你打开的所有终端或者命令行，然后运行安装包，并且启动一个新的终端。你可以使用`npm --version`和`node --version`来验证你的安装是否完全无误。如果出现错误，你需要解决这些问题才能继续下面的步骤。

### Ionic CLI 和 Cordova {#ionic-cli-and-cordova}

Node和NPM安装完成之后，我们继续安装Ionic和Cordova CLI.

```
$ npm install -g ionic cordova
```

> 注意：`-g`代表着全局安装，因此在windows环境下你需要以管理员的身份来运行命令行，在Mac/Linux下，需要使用`sudo`来运行此命令。

上面的步骤完成后，开始创建你的第一个app:

```
$ ionic start helloWorld blank
```

接下来运行app，使用`cd` 命令进入创建app的目录，然后运行`ionic serve`测试一下你的app是否能够在浏览下正常打开。

```
$ cd helloWorld
$ ionic serve
```



