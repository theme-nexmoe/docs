# 快速开始

在使用 Nexmoe 之前，请仔细阅读 [Hexo 的官方文档](https://hexo.io/zh-cn/docs/)，完成对 Hexo 的安装，并完成对 `config.yml` 的基本配置（标题、介绍、作者、时区、语言等）

## 遇到问题怎么办？

### 1、查阅 Hexo 官方文档

一般遇到的问题都是对 Hexo 不熟悉导致的，本主题作者也不是很了解 Hexo，所以经常会去看官方文档。

Hexo 官方文档解决大部分问题！

请仔细阅读 [Hexo 的官方文档](https://hexo.io/zh-cn/docs/)

请仔细阅读 [Hexo 的官方文档](https://hexo.io/zh-cn/docs/)

请仔细阅读 [Hexo 的官方文档](https://hexo.io/zh-cn/docs/)

### 2、查阅本文档

本文档内容较少，只解决常见问题

### 3、搜索 GitHub 中的 issue

很多问题在issue中也能找到答案 [前往搜索 issue](https://github.com/theme-nexmoe/hexo-theme-nexmoe/issues)

### 4、使用搜索引擎

以上方法解决不了的问题，搜索引擎一定能解决，如果搜索引擎都解决不了，那就没办法了。



## 使用 NPM 安装主题

```
npm i hexo-theme-nexmoe
```

## 安装 WordCount（必须）

其他主题不同，安装 Nexmoe 需要额外的步骤；主题默认已经集成了文章【字数统计】、【阅读时长】统计功能，且暂时无法关闭。如果没有安装 hexo-wordcount 插件，先安装该插件：

```bash
npm i --save hexo-wordcount
```

**Node 版本 7.6.0 之前,请安装 2.x 版本 \(Node.js v7.6.0 and previous\) ，安装命令如下：**

```bash
npm install hexo-wordcount@2 --save
```

## 启用 Nexmoe

在 `config.yml` 中，修改 `theme` 的值为 `nexmoe`

## 运行 Nexmoe

在站点根目录下运行下面的命令在本地启动一个 Hexo Server。

```bash
hexo s --debug
```

> 在服务启动的过程，注意观察命令行输出是否有任何异常信息，如果你碰到问题，这些信息将帮助他人更好的定位错误。

当命令行输出下述内容时说明 Hexo 已经监听在本机的 4000 端口，使用浏览器访问 [http://localhost:4000](http://localhost:4000) ，检查站点是否正确运行。

```bash
INFO  Hexo is running at http://localhost:4000/. Press Ctrl+C to stop.
```

> 如果你在使用过程中遇到问题，请尝试在文档中进行搜索，或者在 GitHub 上 提出 [issue](https://github.com/nexmoe/hexo-theme-nexmoe/issues/new)

## 更新 Nexmoe

使用 NPM 的 install 命令即可升级

```
npm i hexo-theme-nexmoe
```

