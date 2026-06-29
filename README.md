# wxad-ipworkshop-pickpictures

图片分类 / 挑选工具（前端纯静态页面）。

## 在线访问

- EdgeOne Pages：<https://wxad-ipworkshop-pickpictures-7s2vs437.edgeone.dev>

## 目录结构

```
.
├── image-classifier_副本.html   # 源码页面（可直接用浏览器打开）
├── assets_副本/                 # 依赖资源（xlsx 解析库等）
│   └── xlsx.full.min.js
└── dist_副本/                   # 构建产物，用于部署
    ├── index.html
    └── assets/
```

## 本地预览

直接用浏览器打开 `image-classifier_副本.html` 或 `dist_副本/index.html` 即可。

## 部署

`dist_副本/` 目录可直接部署到任意静态托管平台：

- EdgeOne Pages
- GitHub Pages
- Vercel / Netlify 等
