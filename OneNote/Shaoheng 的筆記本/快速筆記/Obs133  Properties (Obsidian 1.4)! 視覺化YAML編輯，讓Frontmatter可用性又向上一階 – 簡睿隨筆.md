剪輯自: [https://jdev.tw/blog/8152/obs133-properties-obsidian-1-4-%E8%A6%96%E8%A6%BA%E5%8C%96yaml%E7%B7%A8%E8%BC%AF%EF%BC%8C%E8%AE%93frontmatter%E5%8F%AF%E7%94%A8%E6%80%A7%E5%8F%88%E5%90%91%E4%B8%8A%E4%B8%80%E9%9A%8E](https://jdev.tw/blog/8152/obs133-properties-obsidian-1-4-%E8%A6%96%E8%A6%BA%E5%8C%96yaml%E7%B7%A8%E8%BC%AF%EF%BC%8C%E8%AE%93frontmatter%E5%8F%AF%E7%94%A8%E6%80%A7%E5%8F%88%E5%90%91%E4%B8%8A%E4%B8%80%E9%9A%8E)  
彙總Obsidian最近幾個大版本添加的新功能：

- v1.0: Tabs
- v1.1: Canvas
- v1.2: Bookmarks
- v1.3: New PDF viewer
- v1.4: Properties

## 1. Properties (特性，性質)

我們使用中的筆記就是個電子檔案，檔案具有作業系統指派的檔案屬性（路徑檔名、建檔時間、最後存取時間等），而編輯中的純文字檔就是透過最開頭的YAML區為筆記賦予了自訂的屬性（或特性），例如編輯中的讀書筆記就可以有專用的特性：

- 作者姓名
- 出版日期
- 出版社
- 閱讀起迄日期
- ...

YAML區的這些自訂的特性（Frontmatter）擴充了純文字本身內容以外的意義，由文字延伸成可供再利用的資料，再藉由Dataview外掛（或開發中的核心外掛Datacore）就能再由資料中萃取成資訊。  
[!TIP]+ PKM的目標  
文字→資料→資訊→知識

## 2. Properties相關重點

### 2.1. 新增命令

- Add file property (預設按鍵：Ctrl/Cmd+;)
- Edit file property
- Clear file prolperties
- Properties Core plugin: Show all properties
- Properties Core plugin: Show file properties  
    

### 2.2. 設定

- YAML區顯示切換：Settings→Editor→Display→Show file properties
- Properties Core plugin: 將全部或檔案的YAML顯示成獨立窗格

### 2.2. 設定

### 2.3. Property type (特性種類)

YAML欄位的類型：

- Text：文字類型
- List：清單類型
- Number：數值類型
- Checkbox：核取盒（真假值）
- Date：日期類型
- Time：日期＋時間類型

### 2.4. 操作

- 最開頭的Properties可切換顯示/隱藏
- 點擊最左側的圖示可顯示功能單
    
    - 由Property type指定此特性的種類
    - 用Remove移除不需要的特性 (點擊圖示後按 Del比較快)
- 點擊左側圖示後，移動游標到另一個圖示按 Shift+Click即可多行選取
- 點擊左側圖示後可拖拉該行，放開即可移動到新位置  
    

## 3. Properties的好處

- **一致性**：雖然YAML區可 透過模板來產生初始的內容，但假以時日， 特性和標籤都面臨不易管理的問題，透過核心外掛的功能可以降低管理成本，讓特性逐漸達到一致性的運用
- **搜尋**：點擊特性窗格的特性後，能搜尋出使用該特性的筆記
- **易用性**：方便入門者使用Frontmatter的門檻，透過種類的輸入檢核可確保輸入正確格式的資料值  
    
    1. 在我的模板裡使用下列方法在建立新筆記時可挑選筆記種類：
 
## 3. Properties的好處

## 4. 已知問題

---￼type: {{FT_type:choice:專案筆記:彙總筆記:閱讀筆記:永久筆記}}￼---  
但目前Properties外掛不會排除模板的值而造成問題：  

![gh|600](Exported%20image%2020241106113840-0.png)

1. Linter修改時間無法更新  
    

## 5. Attribute vs Property (屬性與特性)

- The difference is subtle. Attributes are refering to additional information of an object. Properties are describing the characteristics of an object. Most people use these two words as synonyms.
- 差異是微妙的。屬性是指物件的附加資訊。特性是描述物件的特徵。大多數人將這兩個詞視為同義詞。

## 5. Attribute vs Property (屬性與特性)

[!COMMENT]+ Attribute vs Property

## 6. 相關鏈接

- v1.4 Release note: [https://obsidian.md/changelog/2023-07-26-desktop-v1.4.0/](https://obsidian.md/changelog/2023-07-26-desktop-v1.4.0/)￼

## 7. 教學影片

## 7. 教學影片

![Embedded YouTube video](https://www.youtube.com/embed/z-50Rx5P0oE?feature=oembed&autoplay=true)