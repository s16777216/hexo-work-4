---
title: Hexo 1 - 基本指令
date: 2024-05-22 21:00:52
categories:
  - hexo
tags: 
  - hexo
---

## 安裝

```bash
  npm install -g hexo-cli
```

## 初始化

```bash
  hexo init blog
  cd blog
  npm install
```

## 本地預覽

```bash
  hexo server
```
### 指定 port，預設為 5000
```bash
  hexo server -p 5000
```

## 產生靜態檔案

```bash
  hexo generate
```

## 部署

```bash
  hexo deploy
```

## 清除快取

```bash
  hexo clean
```

## 產生新文章

```bash
  hexo new "測試"
```

## 產生新草稿

```bash
  hexo new draft "測試"
```

## 產生新分類

```bash
  hexo new page "測試"
```

## 參考資料

[指令 | Hexo](https://hexo.io/zh-tw/docs/commands)