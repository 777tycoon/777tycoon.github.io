---
title: HEXO-NexT如何做出選單功能
date: 2024-11-25 10:16:37
tags:
  - hexo
categories: hexo教學
---


在 **Hexo** 中使用 **NexT 佈景主題** 設置 **Menu（選單）** 可以讓你的網站更具結構性。以下是完整的設置步驟：

---

### 🛠 **步驟 1: 打開 NexT 配置文件**

1. 前往你的 **Hexo 根目錄**。
2. 打開 **NexT 主題配置文件**，通常位於：

```
yamlthemes/next/_config.yml
```


---

### 📝 **步驟 2: 編輯 Menu 設定**

找到配置文件中的 **menu** 區塊，通常看起來像這樣：

```yaml
menu:
  home: / || fa fa-home
  about: /about/ || fa fa-user
  tags: /tags/ || fa fa-tags
  categories: /categories/ || fa fa-th
  archives: /archives/ || fa fa-archive
  contact: /contact/ || fa fa-envelope
```

---

### 🧩 **Menu 配置詳解**

每一行都有三個部分：

```yaml
menu_item: 路徑 || 圖標
```

- **`menu_item`**：選單項目的名稱（例如 `home`, `about` 等）。
- **`路徑`**：指向的 URL 路徑（例如 `/about/`）。
    - 根目錄頁面使用 `/`。
    - 其他頁面使用 `/page-name/`。
- **`圖標`**：使用 **Font Awesome** 圖標（可選）。
    - 例如：`fa fa-home` 代表首頁圖標。

---

### 🧩 **新增自定義 Menu 項目**

假設你要添加一個 **「作品集」** 選單項目：

```yaml
menu:
  home: / || fa fa-home
  about: /about/ || fa fa-user
  portfolio: /portfolio/ || fa fa-briefcase   # 新增作品集
  tags: /tags/ || fa fa-tags
  categories: /categories/ || fa fa-th
  archives: /archives/ || fa fa-archive
```

---

### 🌐 **多層選單（子選單）**

NexT 也支援子選單，可以這樣設置：

```yaml
menu:
  home: / || fa fa-home
  about: /about/ || fa fa-user
  more:
    sublist:
      projects: /projects/ || fa fa-code
      contact: /contact/ || fa fa-envelope
```

---

### 🔄 **步驟 3: 重新生成並部署**

設置完成後，重新生成並部署你的網站：

```bash
hexo clean
hexo generate
hexo deploy
```

---

### 🚀 **完成後檢查**

開啟你的網站，確認選單是否按照設置顯示。如果有問題，可以檢查配置文件的語法或重啟 Hexo 本地伺服器：

```bash
hexo server
```

---

### 📌 **小提示**

- **Font Awesome 圖標**：可以在 [Font Awesome 網站](https://fontawesome.com/icons) 查找更多圖標。
- **順序調整**：修改配置文件中選單項目的順序會影響它們在網站上的排列順序。

有需要更多調整或特定需求嗎？隨時告訴大亨！