---
title: Hexo 調整網站的永久連結（Permalinks）
date: 2024-05-25 18:32:45
categories:
  - hexo
tags:
  - hexo
---

## 設定根目錄的_config.yml

```yml
# permalink: :year/:month/:day/:title/ 預設
permalink: :category/:name/
```

### 變數

|            變數 | 描述                                          |
|--------------:|:--------------------------------------------|
|       `:year` | 	文章的發表年份（4 位數）                              |
|      `:month` | 文章的發表月份（2 位數）                               |
|    `:i_month` | 	文章的發表月份（去掉開頭的零）                            |
|       `:day`	 | 文章的發表日期 (2 位數)                              |
|     `:i_day`	 | 文章的發表日期（去掉開頭的零）                             |
|      `:hour`	 | 文章發表時的小時 (2 位數)                             |
|     `:minute` | 	文章發表時的分鐘 (2 位數)                            |
|     `:second` | 	文章發表時的秒鐘 (2 位數)                            |
|      `:title` | 	檔案名稱 (relative to “source/_posts/“ folder) |
|       `:name` | 	檔案名稱                                       |
| `:post_title` | 	文章標題                                       |
|  `:category`	 | 分類。如果文章沒有分類，則是 `default_category` 設定。       |

* `default_category` 預設為 `uncategorized`，可以在 `_config.yml` 中修改。

## 參考資料

[Hexo - 永久連結（Permalinks）](https://hexo.io/zh-tw/docs/permalinks.html)