---
title: Hexo 2 - 修改導航列
date: 2024-05-25 17:31:48
categories:
   - hexo
tags:
   - hexo
---

## 事前準備

[安裝Theme](./hexo/hexo-extra-1/)

## 修改導航列

### 修改 _config.yml

```yml
  # Header
    menu:
      Home: /
      Archives: /archives
      Categories: /categories
      Tags: /tags
      <View_Name>: <View_Path>
```

1. 在 ```./themes/landscape/_config.yml``` 中找到 ```#header```，
2. 修改成自己想要的導航列。
   * ```<View_Name>```: 顯示名稱，可以是中文
   * ```<View_Path>```: 連結路徑


## 參考資料

[(10) 試著學 Hexo - 新增頁面](https://ithelp.ithome.com.tw/articles/10241736)