---
description: 本页文档适用于 Hexo 5.0 后使用 npm 安装
---

# 主题配置

安装好主题后，在 Hexo 根目录下新建  `_config.nexmoe.yml` 

然后对照 `node_modules/hexo-theme-nexmoe/_config.yml` 进行修改，

理论上 `_config.nexmoe.yml` 会覆盖默认配置

### site\_verification

向搜索引擎验证你对站点的所有权，用于向搜索引擎提交 sitemap 和管理站点被搜索引擎收录的情况。

```yaml
site_verification:
  google:
  baidu:
```

获取 site\_verification 值的方法： 1. 登录搜索引擎后台，添加站点后，验证所有权时选择 `HTML 标记` 方式。搜索引擎接下来会告诉你把类似于一串下面的东西添加到你的页面中：

```text
<meta name="xxxx-site-verification" content="xxxxxxxxxxxxxxxx" />
```

1. 将 xxxxxxxxxxxxxxxx 字符串复制出来，填入 `主题配置文件` 中对应搜索引擎的设置中，站点重新部署以后即可通过验证。

> 如果你启用了 `Google Analytics`，可以直接在 `Google Webmaster` 验证，无需再次使用 html 标记验证。

### 版权协议

你可以设置所有文章的版权协议，这将会显示在文章结尾；支持 `HTML`。版权中会包含 `本文作者、本文链接和协议` 等信息。

比如，你可以这样设置：

```yaml
copyright: '<strong>版权声明：</strong>本文采用 <a href="https://creativecommons.org/licenses/by-nc-sa/3.0/cn/deed.zh" target="_blank">CC BY-NC-SA 3.0 CN</a> 协议进行许可'
```

你也可以在文章的 `Front-Matter` 中覆盖这一设置

```yaml
copyright: '<strong>版权声明：</strong>本文采用 <a href="https://creativecommons.org/licenses/by-nc/3.0/cn/deed.zh" target="_blank">CC BY-NC 3.0 CN</a> 协议进行许可'
```

同时你可以使用下面的 `Front-Matter`

```yaml
hide_copyright: true
```

来隐藏本篇文章的版权协议

