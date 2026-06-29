# wxad-ipworkshop-pickpictures

图片分类 / 挑选工具（前端纯静态页面）。

## 在线访问

- **GitHub Pages**：<https://yaojz9611-max.github.io/wxad-ipworkshop-pickpictures/>
- EdgeOne Pages：<https://wxad-ipworkshop-pickpictures-7s2vs437.edgeone.dev>

## 目录结构

```
.
├── image-classifier.html   # 源码页面（可直接用浏览器打开）
├── assets/                 # 依赖资源（xlsx 解析库等）
│   └── xlsx.full.min.js
└── dist/                   # 构建产物，用于部署
    ├── index.html
    └── assets/
```

## 本地预览

直接用浏览器打开 `image-classifier.html` 或 `dist/index.html` 即可。

## 部署

`dist/` 目录可直接部署到任意静态托管平台：

- GitHub Pages（当前已启用，Source = `main` / `/dist`）
- EdgeOne Pages
- Vercel / Netlify 等
