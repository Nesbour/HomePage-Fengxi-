# 风汐 · Personal Homepage

一个以蓝紫色为主色调的个人主页，采用原生 HTML、CSS 和 JavaScript 编写，无需安装依赖或构建工具。

演示站：https://fengxinzi.kdns.fr

## 功能特点

- 响应式布局：适配桌面端与手机端
- 蓝紫色渐变视觉风格与柔和背景装饰
- 深色 / 浅色主题切换
- 社交平台入口与统一图标风格
- 卡片悬浮、渐变光晕、轻量 3D 倾斜等鼠标交互
- `prefers-reduced-motion` 动效偏好适配
- Email 按钮使用 `mailto:`，点击后向 `Chumen00@outlook.com` 撰写邮件
- 头像资源已内嵌在 HTML 中，不需要额外图片文件

## 本地预览

直接使用浏览器打开仓库根目录下的 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 将本项目中的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，然后保存。
6. 等待 GitHub Pages 完成部署，页面地址会显示在 Pages 设置页面。

## 自定义

可直接编辑 `index.html` 修改个人介绍、社交链接、颜色和页面样式。

## 说明

- 邮件按钮通过访客设备上的默认邮件客户端打开；如果访客没有配置邮件客户端，可能无法自动弹出写信窗口。
- 本项目没有附带开源许可证。若希望他人复用或修改代码，请先自行选择并添加合适的 LICENSE 文件。
