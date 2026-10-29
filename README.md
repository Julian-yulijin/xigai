# xigai · 文化三章

以三个切面观察中国文化：**文化自信**、**文化交流**、**文化安全**。

纯静态站点（HTML / CSS / JS），无构建依赖，由 GitHub Actions 自动部署到 GitHub Pages。

## 页面

| 文件 | 篇章 | 内容 |
| --- | --- | --- |
| `index.html` | 壹 · 文化自信 | 何为自信、非遗名录、民乐出海、当代传承者 |
| `exchange.html` | 贰 · 文化交流 | 民间视角（游戏/网文/动漫/剧集/微短剧）、国际宏观视角（文化年、引进来与走出去） |
| `security.html` | 叁 · 文化安全 | 六类风险、五个提醒、《国家安全法》第二十三条摘录 |
| `tree.html` | 肆 · 我们的树 | 互动内容页 |
| `文化三章_分享版.html` | 单文件版 | 四个篇章合并为一个文件，方便离线分享 |

## 目录结构

```
.
├── index.html
├── exchange.html
├── security.html
├── tree.html
├── 文化三章_分享版.html
├── assets/
│   ├── css/style.css
│   └── js/main.js
└── .github/workflows/pages.yml
```

## 本地预览

直接双击 `index.html`，或起一个静态服务器：

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

推送到 `main` 分支后，`.github/workflows/pages.yml` 会自动发布到 GitHub Pages。
首次运行时会自动为仓库启用 Pages（`actions/configure-pages` 的 `enablement: true`）。

站点地址：<https://julian-yulijin.github.io/xigai/>

## 说明

站内史料、年份与法条为科普性整理，正式引用请以官方发布文本为准。
