# 个人主页

一个简洁现代的个人网站，纯静态 HTML/CSS/JS，零依赖，由 GitHub Pages 托管。

## 在线访问

👉 https://3698737270.github.io/git/

## 特性

- 🎨 现代单页设计，含头像、简介、技能、项目、联系方式
- 🌗 深色 / 浅色主题切换（自动记忆偏好，默认跟随系统）
- 📱 完全响应式，适配手机与桌面
- ✨ 滚动入场动画
- ⚡ 零依赖，单个 HTML 文件即可运行

## 本地预览

直接用浏览器打开 `index.html` 即可，或启动本地服务器：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 自定义

编辑 `index.html` 中以下内容即可：

- `你的名字` → 替换成你的名字
- Hero 区域的 `role` 和 `intro` → 你的职业与简介
- `#skills` 区的 `<span class="tag">` → 你的技能
- `#projects` 区的 `.card` → 你的项目
- `#contact` 区的社交链接 → 你的联系方式

## 部署

推送到 `main` 分支后，GitHub Pages 会自动更新（Settings → Pages → Source 选择 `main` 分支根目录）。
