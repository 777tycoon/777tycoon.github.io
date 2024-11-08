---
title: HEXO學習日誌
date: 2024-11-04 09:39:03
tags:
  - hexo
categories: hexo教學
---

# HEXO學習日誌

從 GOOGLE BLOGGER 到 WORDPRESS 到...N...到 OBSIDIAN+MIXA 到 現在 OBSIDIAN+HEXO

2024-11-04
- 如何安裝Git Bash?
- 發現了很好用的VS code
本來發第一篇文都失敗，原來推送到Github也有時間差，過一陣子看網站就出現更新了
- 如何更換主題(theme) 
更換後測試發現 WARN No layout: index.html
原來是主題的檔名錯了，"hexo-theme-next-master" 打成了"hexo-theme-next" 
改回來後在本地端就可正常的顯示了

2024-11-05
- 不知道為何我的網站還是沒有更新成 Next 的主題
- 原來是忘記先鍵入"生成(generate)" 再 Deploy，重新做一次後就可以正常顯示新主題了
- 發現幾個還有在用 HEXO 並持續更新的部落格(用戶好像多以中文為主)
[Marsen's Blog](https://blog.marsen.me/)
[Code and Me(Kyomind)](https://blog.kyomind.tw/)
[是 Ray 不是 Array](https://israynotarray.com/)

- 希望改從 Cloudflare 發布網站 參考:[把hexo博客部署到Cloudflare Pages - 阿加尔塔之风](https://www.jgduhao.xyz/2023/08/06/%E6%8A%8Ahexo%E5%8D%9A%E5%AE%A2%E9%83%A8%E7%BD%B2%E5%88%B0Cloudflare-Pages/)、[【Hexo】使用cloudflare pages自动化部署hexo_cloudfare page-CSDN博客](https://blog.csdn.net/muxuen/article/details/141484848)
- [Cloudflare | Web Performance & Security](https://dash.cloudflare.com/bd8965044ef67b9e745c4ca1d408167f/pages/new/provider/github)
- 如何做出搜尋功能

2024-11-08
今天早上弄了好久，output檔一直找不到Public，於是更改output檔名為 2024 (我以為output的資料夾是2024)，終於成功部署網站到Cloudflare了，但喜悅一下落空，因為不知道為什麼還是不能看到，後來我又改了一次重點就是要在找到package.json檔，好像也是要買網域名才能用，有點像白忙一場，不過還是蠻有成就感
## HEXO 從零開始

先是下載 git bash 軟體

git bash 基本指令 參考: [[教學] git-4 bash基本指令操作 - 討論區  |   NVDA 台灣](https://www.nvda.org.tw/discussion/ui=100200tm=1952161285)
在 git bash 中，路徑都是以 `/` 正斜線來隔開，如果是 D 槽則是以 `/d` 來表示，

這稱為絕對路徑，就是從最前面的根目錄開始寫起，`/` 就是代表根目錄。

cd 資料夾 就可以切換到你要的資料夾了，根據經驗我直接把部落格資料夾 copy+paste 到我想要的硬碟槽可以直接使用

第二行，也就是游標所在行，前面有一個錢號，這是 git bash 的指令列提示符號，在輸入指令時不需輸入該符號喔。



## 參考連結
[javascript - Hexo 搭建与部署指南 - 个人文章 - SegmentFault 思否](https://segmentfault.com/a/1190000042111533)
[基于Hexo的matery主题搭建博客并深度优化 | 悟尘记 - 李小龙的博客网站](https://www.lixl.cn/2019/092856736.html#toc-heading-3)
[Markdown + Gitbook · GitBook](https://alecthw.github.io/books/markdown-simple-world/4.html)
大家都推薦的[NexT](https://github.com/next-theme)
[关于我使用obsidian加hexo部署个人博客的过程 - SagiRastar's Blog](https://sagi-rastar.github.io/2023/11/10/%E5%85%B3%E4%BA%8E%E6%88%91%E4%BD%BF%E7%94%A8obsidian%E5%8A%A0hexo%E9%83%A8%E7%BD%B2%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E7%9A%84%E8%BF%87%E7%A8%8B/)
[架設 Hexo+GitHub | 是 Ray 不是 Array](https://israynotarray.com/hexo/20190411/932826160/)
HEXO核心團隊人物的Blog(即便是中文，我還是看不太懂他的文章，太高深了): [首页 | Sukka's Blog](https://blog.skk.moe/)