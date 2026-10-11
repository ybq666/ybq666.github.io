# Boquan Yao (姚博全) - Academic Homepage

This is the personal academic homepage for **Boquan Yao (姚博全)**, hosted on GitHub Pages:
👉 **[https://ybq666.github.io](https://ybq666.github.io)**

Designed specifically for **OpenReview registration**, conference submissions, and academic profile verification.

---

## 快速自定义指南 (Customization Guide)

### 1. 更换个人正装照片 / 头像
- 将你的个人照片命名为 `avatar.jpg` 并放置在本仓库根目录下。
- 网页会自动优先加载 `avatar.jpg`；若无，则自动降级显示优雅的矢量剪影 `avatar.svg`。

### 2. 修改个人基本信息与学术机构
- 打开 `index.html`：
  - 搜索 `Boquan Yao` 或 `姚博全`：修改中英文姓名。
  - 搜索 `Nanjing University` / `南京大学`：修改为你所在的大学、院系或实验室。
  - 搜索 `boquanyao@smail.nju.edu.cn`：修改为你在 OpenReview 上注册填写的官方学术邮箱（.edu 邮箱）。

### 3. 添加 / 修改论文与预印本 (Publications)
- 在 `index.html` 中的 `<section id="publications">` 区块：
  - 复制或修改 `<article class="publication-item">` 节点。
  - 填入论文题目、作者列表（你的名字加上 `<span class="author-self">...</span>` 会自动加粗下划线）。
  - 点击 `[BibTeX]` 按钮可直接展开并复制学术引用。

### 4. 外部学术主页链接
- 在 `index.html` 的头部和底部的 Contact 区块中，替换你的真实学术主页链接：
  - Google Scholar 链接
  - ORCID 链接
  - OpenReview 个人 Profile 链接

---

## 页面特色
- **极简纸质论文排版**：采用经典学术衬线字体与优雅排版结构，沉稳严谨，专为同行评审与学术委员会阅读优化。
- **零外部资源依赖**：纯原生 HTML + CSS + JS 单文件架构，秒级全球加载，不依赖任何第三方 CDN，杜绝因网络波动导致的审核页面打不开。
- **交互友好**：支持可折叠展开的 BibTeX 引用块与亮暗色主题自适应切换。
