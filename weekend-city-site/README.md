# 周末成行 · 上海

大学生周末城市探索指南：根据偏好、天气、预算与同行人数，生成可直接执行的周末路线，支持组队决策、雨天 Plan B、打卡点亮街区和攻略分享。

本仓库为纯静态前端展示（单文件 `index.html`），无需构建，可直接通过 GitHub Pages 访问。

## 在线预览

推送到 GitHub 后，通过 Settings → Pages 启用（本仓库已附带 GitHub Actions 自动部署配置，推送后依次确认 Settings → Pages → Build and deployment → Source 为 **GitHub Actions** 即可）。

## 本地预览

```bash
cd weekend-city-site
python3 -m http.server 8000
```

浏览器打开 http://localhost:8000 即可。

## 目录结构

```text
weekend-city-site/
├── index.html    全部页面与交互（单文件）
├── README.md     项目说明
└── .github/workflows/deploy.yml  自动部署配置
```

## 说明

- 页面内的活动、店铺与价格为演示用样例数据。
- 图片来自 Unsplash 线上资源，预览需保持联网。
