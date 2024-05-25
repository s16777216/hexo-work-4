---
title: Hexo 5 - 部屬至 Github Pages
date: 2024-05-25 20:16:56
categories:
  - hexo
tags:
  - hexo
---

## 安裝 Hexo Deployer Git

```bash
  npm install hexo-deployer-git --save
```
[Github Page](https://github.com/hexojs/hexo-deployer-git)

## 修改 _config.yml

```yml
...

url: https://<username>.github.io/<repository>/ # 你的 Github Pages 網址

...

deploy:
  type: git
  repo: <repository url>
  branch: <branch>
```
* `repo`: 你的 Github Pages repository URL
* `branch`: 你的 Github Pages repository branch

## 參考設定

[佈署 | Hexo](https://hexo.io/zh-tw/docs/one-command-deployment#Git)