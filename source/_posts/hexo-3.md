---
title: Hexo 3 - 插入本地圖片
date: 2024-05-25 17:57:45
categories:
  - hexo
tags:
    - hexo
---

## 事前知識

### Markdown 插入圖片語法

```markdown
    ![圖片說明](圖片路徑)
```

## 開啟設定

### 修改根目錄的_config.yml

```yml
  post_asset_folder: true
```

這樣在產生新文章時就會自動產生一個與文章同名資料夾，用來存放圖片。

## 參考資料

[資產資料夾 | Hexo](https://hexo.io/zh-tw/docs/asset-folders.html)

[在Hexo文章中插入圖片](https://wst24365888.github.io/add-image/)