# FIRE 规划计算器 / FIRE Planning Calculator

一个在浏览器本地运行的 FIRE（财务自由、提前退休）规划工具：输入年龄、资产、房贷、开销，一眼看到 Lean / 标准 / Coast / Barista 四条 FIRE 路径各需几年，并模拟多年税务路径、蒙特卡洛风险、房贷处理方式与社保/ACA/RMD/IRMAA。

A browser-local FIRE (Financial Independence, Retire Early) planning tool: enter age, assets, mortgage and spending to see years-to-FIRE across Lean / Standard / Coast / Barista paths, with multi-year tax-path simulation, Monte Carlo risk view, mortgage treatments, and Social Security / ACA / RMD / IRMAA modeling.

中英双语，右上角一键切换。Bilingual (中文/English toggle, top right).

## 使用 / Usage

直接用浏览器打开 `index.html` 即可，无需安装、无需服务器。
Just open `index.html` in a browser. No install, no server.

也可部署到 GitHub Pages：仓库设置 → Pages → 选择分支即可。
Or deploy via GitHub Pages: Settings → Pages → pick a branch.

## 隐私 / Privacy

- 所有计算都在你的浏览器本地完成，输入的数据只存在页面内存里，关闭或刷新页面即清空。
- All computation runs locally in your browser. Inputs live only in page memory and are cleared on close/refresh.
- 截图导入的 OCR 在本地运行（tesseract.js 在浏览器内执行），图片和数字不会上传到任何服务器。
- Screenshot-import OCR runs locally (tesseract.js executes in-browser). Images and numbers are never uploaded anywhere.
- 页面从 CDN 加载两个第三方资源：tesseract.js（OCR 引擎，jsdelivr）和 Google Fonts（字体）。除此之外无外部请求、无统计、无追踪。
- The page loads two third-party resources from CDNs: tesseract.js (OCR engine, via jsdelivr) and Google Fonts. No other external requests, no analytics, no tracking.
- 可用浏览器 DevTools 的 Network 面板自行验证。
- Verify yourself with the DevTools Network panel.

## 免责声明 / Disclaimer

本工具仅用于个人财务规划测算，不构成投资建议。税率与政策为简化模型，正式申报请咨询 CPA。
Planning tool only, not investment advice. Tax rates and policies are simplified models; consult a CPA for actual filings.

## 许可 / License

MIT — 详见 LICENSE。
