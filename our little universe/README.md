# 我们的小宇宙

一个纯静态情侣纪念网页，可以直接部署到 Vercel。

## 部署到 Vercel

1. 把整个文件夹上传到 GitHub 仓库，确保根目录里有 `index.html`、`our-little-universe.html`、`vercel.json`。
2. 在 Vercel 新建项目，选择这个 GitHub 仓库。
3. Framework Preset 选择 `Other` 或保持默认静态项目。
4. Build Command 留空，Output Directory 留空。
5. 部署后直接打开 Vercel 给你的根网址即可，不需要手动加 `/our-little-universe.html`。

## 注意

- 默认密码是 `ourstar2026`。
- 当前版本是纯前端，本地上传的照片、留言、愿望会保存在当前设备浏览器里。
- 如果要两个人不同手机实时同步，需要接入 Supabase/Firebase/Vercel KV + Blob 这类后端存储。
- 不要把真实 DeepSeek API Key 写进前端代码；如果要启用 AI 情书，建议通过后端代理。
