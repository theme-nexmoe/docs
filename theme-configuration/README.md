--
description: This page is for Hexo 5.0 onwards using npm installation
---

# Theme configuration

After installing the theme, create a new `_config.nexmoe.yml` in the Hexo root directory 

and modify it against `node_modules/hexo-theme-nexmoe/_config.yml`.

Theoretically `_config.nexmoe.yml` will override the default configuration

### site\_verification

Verifies your ownership of the site to search engines, is used to submit sitemap to search engines and to manage the site's indexing by search engines.

```yaml
site_verification:
  google:
  baidu:
```

To get the site\_verification value: 1. Log in to the search engine backend, add the site and then select the ``HTML tag'' method when verifying ownership. The search engine will then tell you to add something like the following string to your page.

```text
<meta name="xxxx-site-verification" content="xxxxxxxxxxxxxxxxxxxxx" />
```text

1. Copy the xxxxxxxxxxxxxxxxxxxx string and fill in the search engine settings in the ``theme profile`'' and the site will be validated after redeployment.

> If you have `Google Analytics` enabled, you can validate directly in `Google Webmaster` without having to use the html tags again.

### Copyright agreement

You can set the copyright agreement for all articles, which will be displayed at the end of the article; `HTML` is supported. The copyright will contain information such as `author of this article, link to this article and agreement`.

For example, you could set it like this.

```yaml
copyright: '<strong>Copyright notice:</strong> This article is published under <a href="https://creativecommons.org/licenses/by-nc-sa/3.0/cn/deed.zh" target="_blank">CC BY-NC-SA 3.0 CN</a> protocol for licensing'
```

You can also override this setting in the ``Front-Matter`` of the article

```yaml
copyright: '<strong>Copyright notice:</strong> This article is licensed under the <a href="https://creativecommons.org/licenses/by-nc/3.0/cn/deed.zh" target="_blank">CC BY- NC 3.0 CN</a> license.'
```

Also you can use the following ``Front-Matter``

```yaml
hide_copyright: true
```

to hide the copyright agreement for this article

