# Apple Chen 作品集网页

这是从原始单文件 HTML 拆分出的可部署网页版本。视觉样式、鼠标效果、滚动动效、项目切换、加载页和返回逻辑均保留。

## 目录

- `index.html`：网站首页（部署入口）
- `resume.html`：简历页
- `projects/`：8 个独立项目页
- `assets/images/`：页面图片
- `assets/fonts/`：本地字体与字体样式
- `asset-manifest.json`：资源拆分清单

## 本地查看

不要直接双击 `index.html`。请在此目录启动本地服务器：

```bash
python3 -m http.server 8000
```

然后浏览器打开：`http://localhost:8000`

## 部署原则

上传时必须保留整个目录结构，不能只上传 `index.html`。静态托管平台应把本目录设置为发布目录。
