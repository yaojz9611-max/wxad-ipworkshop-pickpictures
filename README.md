# wxad-ipworkshop-pickpictures

图片分类 / 挑选工具（前端纯静态页面）。

## 在线访问

本仓库部署了两个独立站点，URL 互不干扰：

| 站点 | 用途 | 地址 |
|---|---|---|
| 图片分类工具 | query 图人工分类 / 打标 | <https://yaojz9611-max.github.io/wxad-ipworkshop-pickpictures/> |
| 配置合并器 | 把导出的 groups 合并进 world_cup_avatar.json | <https://yaojz9611-max.github.io/wxad-ipworkshop-pickpictures/merge-config/> |

另外 EdgeOne 镜像（仅图片分类工具）：<https://wxad-ipworkshop-pickpictures-7s2vs437.edgeone.dev>

> 配置合并器全程本地运行，不上传任何数据，避免手写括号出错。

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
