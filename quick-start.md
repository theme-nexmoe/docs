# Quick Start

## Quick Start

Before using Nexmoe, please read the [official documentation for Hexo](https://hexo.io/zh-cn/docs/) carefully, complete the installation of Hexo, and complete the basic configuration of the `site profile` \(title, introduction, author, time zone, language, etc.\)

### What should I do if I encounter problems?

#### 1. Check the official Hexo documentation

The problems you encounter are generally caused by unfamiliarity with Hexo, and the author of this topic does not know Hexo very well, so he often goes to the official documentation.

Hexo official documentation solves most of the problems!

Please read [Hexo's official documentation](https://hexo.io/zh-cn/docs/)

Please read [Hexo's official documentation](https://hexo.io/zh-cn/docs/)

Please read [Hexo's official documentation](https://hexo.io/zh-cn/docs/)

#### 2. Consult this document

This document is small, only to solve common problems

#### 3、Use search engine

The above method can not solve the problem, the search engine must be able to solve, if the search engine can not solve, then there is no way.

### Hexo 5.0 following version installation method \(not recommended\)

#### [Download the latest Release version](https://github.com/nexmoe/hexo-theme-nexmoe/releases/latest)

> The latest release version, suitable for most users.

#### [Use Git](https://github.com/nexmoe/hexo-theme-nexmoe)

You can decide which branch you want to use; you can use Git to download Nexmoe and then use `git pull` to update Nexmoe.

```bash
cd themes
git clone https://github.com/nexmoe/hexo-theme-nexmoe.git nexmoe
cd nexmoe
git checkout {branch/tags name/commit hash}
```

### Hexo 5.0 onwards installation method \(recommended\)

```text
npm i hexo-theme-nexmoe
`` `

## Installing Nexmoe

Unlike other themes, installing Nexmoe requires additional steps; the theme has integrated the post [word count] and [reading time] statistics by default, and cannot be turned off for now. If you don't have the hexo-wordcount plugin installed, install it first: ``bash

```bash
npm i --save hexo-wordcount
```

**Before Node version 7.6.0, please install version 2.x \(Node.js v7.6.0 and previous\), the installation command is as follows:**

```bash
npm install hexo-wordcount@2 --save
```

### Enable Nexmoe

In the `site configuration file`, change the value of `theme` to `nexmoe`

### Run Nexmoe

Run the following command in the site root directory to start a Hexo Server locally.

\`\`bash hexo s --debug

```text
> As the service starts, watch the command line output for any exceptions that will help others locate errors if you run into problems.

When the command line outputs the following, Hexo is already listening on port 4000 on the local machine. Use your browser to visit [http://localhost:4000](http://localhost:4000) to check if the site is running correctly.

```bash
INFO Hexo is running at http://localhost:4000/. Press Ctrl+C to stop.
```

> If you have problems using it, try searching the documentation or raising an [issue](https://github.com/nexmoe/hexo-theme-nexmoe/issues/new) on GitHub

### Update Nexmoe

We only recommend npm updates for Hexo 5.0 and later

~~ If you downloaded and installed Nexmoe from the `version release page`, then you need to backup your `theme backup file`, then rename the old theme folder to `nexmoe-old`, rename the new Nexmoe download to `nexmoe`, and migrate the old `theme profile` to the new `theme profile` according to the changelog instructions. to the new `theme profile`. You can delete `nexmoe-old` after testing. ~~

~~ If you installed Nexmoe using Git, you can run a git pull directly under the theme folder to update the theme and rename the previous theme configuration file to `_config.old.yml`, make a copy of `_config.example.yml` and rename it to `_ config.yml`. Migrate your configuration from `_config.old.yml` to the new `_config.yml` and you can delete `_config.old.yml` after testing it. ~~

Translated with www.DeepL.com/Translator \(free version\)

