# 个人作品集网站

这是一个基于纯HTML、CSS和JavaScript构建的个人作品集网站，用于展示项目案例和联系方式。网站设计现代化、响应式，适配各种设备尺寸。

## 网站功能

- **响应式设计**：适配桌面、平板和移动设备
- **现代化UI**：使用CSS变量和现代布局技术
- **作品展示**：网格布局展示项目案例
- **联系信息**：提供电子邮件和社交媒体链接
- **平滑滚动**：页面内导航平滑滚动效果

## 如何部署到GitHub Pages

1. **创建GitHub仓库**
   - 在GitHub上创建一个新的仓库，命名为 `username.github.io`（其中 `username` 是你的GitHub用户名）

2. **上传文件**
   - 将 `index.html` 和 `README.md` 文件上传到仓库

3. **启用GitHub Pages**
   - 进入仓库设置 → Pages
   - 在 "Source" 部分选择 "main" 分支
   - 点击 "Save" 按钮
   - 稍等几分钟，你的网站就会在 `https://username.github.io` 上可用

4. **自定义域名（可选）**
   - 如果你想使用自定义域名（如 `zetasshk.fun`），需要：
     - 在域名注册商处设置DNS记录，将 `zetasshk.fun` 指向 `username.github.io`
     - 在GitHub仓库设置 → Pages → Custom domain 中添加你的域名
     - 保存设置后，GitHub会自动为你的域名生成SSL证书

## 如何自定义网站

1. **修改内容**
   - 编辑 `index.html` 文件，修改个人信息、项目描述和联系信息

2. **修改样式**
   - 在 `index.html` 文件的 `<style>` 部分修改CSS变量和样式规则

3. **添加项目**
   - 在 `<section id="projects">` 部分添加新的项目卡片

4. **修改图片**
   - 目前使用的是生成的图片，你可以替换为自己的项目截图

## 技术栈

- HTML5
- CSS3（使用CSS变量和Flexbox/Grid布局）
- JavaScript（平滑滚动效果）

## 浏览器兼容性

- 现代浏览器（Chrome、Firefox、Safari、Edge）
- 响应式设计适配移动设备

## 许可证

本项目采用 MIT 许可证。