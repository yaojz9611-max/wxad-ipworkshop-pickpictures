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
└── docs/                   # 构建产物（即 GitHub Pages 部署目录）
    ├── index.html
    └── assets/
```

## 本地预览

直接用浏览器打开 `image-classifier.html` 或 `docs/index.html` 即可。

## 部署

`docs/` 目录可直接部署到任意静态托管平台：

- GitHub Pages（当前已启用，Source = `main` / `/docs`）
- EdgeOne Pages
- Vercel / Netlify 等
