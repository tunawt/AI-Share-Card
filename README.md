# AI 对话分享卡

纯静态的 Markdown → 长图 / 切分图 工具。

## 本地运行

直接双击 `index.html` 在浏览器打开即可。所有依赖都在 `./lib/` 下，无网络也能用。

## 部署

任何静态托管平台都行（Cloudflare Pages / GitHub Pages / Vercel / Netlify）。直接把整个目录推上去即可，无需构建。

## 依赖

| 库 | 版本 | 用途 |
|---|---|---|
| marked | 4.3.0 | Markdown 解析 |
| highlight.js | 11.9.0 | 代码语法高亮 |
| KaTeX | 0.16.9 | 数学公式 |
| Mermaid | 10.6.1 | 流程图 |
| html2canvas | 1.4.1 | DOM 截图 |

所有依赖均为 MIT/Apache/BSD 开源协议。
