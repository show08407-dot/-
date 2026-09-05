GitHub Pages 部署：
1. 新建 GitHub repository。
2. 将本目录中的全部文件和 icons 文件夹上传到仓库根目录。
3. Settings -> Pages -> Deploy from a branch -> main -> /(root) -> Save。
4. 等待 Pages 发布后，打开生成的 HTTPS 地址。
5. 将该地址交给 PWABuilder。

文件：
index.html     主程序（稳定解析版）
manifest.json  PWA 配置
sw.js          Service Worker
icons/icon.svg 应用图标
