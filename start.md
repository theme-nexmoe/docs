# Quick start

Before using Nexmoe, please read the [official documentation for Hexo](https://hexo.io/zh-cn/docs/), complete the installation of Hexo and complete the basic configuration of the `site profile` (title, introduction, author, time zone, language, etc.)

## What should I do if I encounter problems?

### 1. Check the official Hexo documentation

Problems are usually caused by unfamiliarity with Hexo, and the author of this topic does not know Hexo very well, so he often goes through the official documentation.

The official Hexo documentation solves most problems!

Please read the official documentation for Hexo carefully (https://hexo.io/zh-cn/docs/)

Please read the [official Hexo documentation](https://hexo.io/zh-cn/docs/)

Please read carefully [Hexo's official documentation](https://hexo.io/zh-cn/docs/)

### 2. Consult this document

This document is small and only addresses frequently asked questions

### 3、Use search engine

The above method can not solve the problem, the search engine must be able to solve, if the search engine can not solve, then there is no way.

## Hexo 5.0 following version installation method (not recommended)

### [Download the latest Release version](https://github.com/nexmoe/hexo-theme-nexmoe/releases/latest)

> The latest release version, suitable for most users.

### [Use Git](https://github.com/nexmoe/hexo-theme-nexmoe)

You can decide which branch you want to use; you can use Git to download Nexmoe and then use ``git pull`` to update Nexmoe.

```bash
cd themes
git clone https://github.com/nexmoe/hexo-theme-nexmoe.git nexmoe
cd nexmoe
git checkout {branch/tags name/commit hash}
```

## Hexo 5.0 onwards installation method (recommended)

```
npm i hexo-theme-nexmoe
```

## Installing Nexmoe

Unlike other themes, installing Nexmoe requires an extra step; the theme has integrated post [word count] and [reading time] statistics by default and cannot be turned off at the moment. If you do not have the hexo-wordcount plugin installed, install it first: ``bash

```bash
npm i --save hexo-wordcount
```

**Before Node version 7.6.0, please install version 2.x \ (Node.js v7.6.0 and previous\) with the following command:**

```bash
npm install hexo-wordcount@2 --save
```

## Enable Nexmoe

In the ``site configuration file``, change the value of ``theme`` to ``nexmoe``

## Run Nexmoe

Run the following command in the site root directory to start a Hexo Server locally.

``bash
hexo s --debug
```

> As the service starts, watch the command line output for any exception messages that will help others locate errors if you encounter problems.

When the command line outputs the following, Hexo is already listening on port 4000 on the local machine. Use your browser to visit [http://localhost:4000](http://localhost:4000) to check that the site is running correctly.

```bash
INFO Hexo is running at http://localhost:4000/. Press Ctrl+C to stop.
```

> If you have problems using it, try searching the documentation or raising an [issue](https://github.com/nexmoe/hexo-theme-nexmoe/issues/new) on GitHub

## Updating Nexmoe

It is currently only recommended to use npm updates for Hexo 5.0 onwards

~~ If you downloaded and installed Nexmoe from the `version release page`, you will need to back up your `theme backup file`, then name the old theme folder `nexmoe-old`, rename the new Nexmoe download to `nexmoe` and follow the instructions in the changelog to migrate the old `theme profile` to the new into the new `theme profile`. You can delete `nexmoe-old` once you have tested it. ~~

~~ If you installed Nexmoe using Git, you can update the theme by running a git pull directly under the theme folder and renaming the previous theme configuration file to `_config.old.yml`, making a copy of `_config.example.yml` and renaming it to `_ config.yml`. Migrate your configuration from `_config.old.yml` to the new `_config.yml` and you can delete `_config.old.yml` once the tests have passed. ~~
