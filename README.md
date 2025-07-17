# 🌸 Korean Portfolio Pure HTML / 韩式个人链接页面纯HTML版

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen)](https://nuomi8844.github.io/korean-portfolio-pure-html/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Ready-orange)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-Modern-blue)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**[English](#english) | [中文](#chinese)**

---

## English

### 🎯 Overview

A beautiful, fully self-contained Korean-style link-in-bio page built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies - just open and use! Perfect for social media profiles, personal branding, or as a landing page.

### ✨ Features

- 🚀 **Zero Dependencies**: Pure HTML/CSS/JavaScript - no frameworks required
- 📱 **Fully Responsive**: Works perfectly on mobile and desktop
- 🎨 **Korean Aesthetic**: Beautiful gradient backgrounds and clean design
- 📸 **Photo Galleries**: Two customizable image galleries with click-to-open links
- 🔗 **Social Links**: Easy-to-customize social media and contact links
- ⚙️ **Admin Panel**: Hidden admin interface for real-time content editing
- 💾 **Local Storage**: Changes persist in browser without server
- 🌐 **Multi-Deploy**: Works on any static hosting (GitHub Pages, Netlify, etc.)
- 🔒 **Password Protected**: Secure admin access with customizable password

### 🚀 Quick Start

#### Option 1: Download ZIP
1. [Download the latest release](https://github.com/nuomi8844/korean-portfolio-pure-html/archive/refs/heads/main.zip)
2. Extract and open `index.html` in your browser
3. That's it! 🎉

#### Option 2: Clone Repository
```bash
git clone https://github.com/nuomi8844/korean-portfolio-pure-html.git
cd korean-portfolio-pure-html
# Open index.html in your browser or run a local server
python -m http.server 8000  # Python 3
# or
npx serve .  # Node.js
```

### 📝 Customization

#### Method 1: Direct HTML Editing (Recommended)
Open `index.html` and find the `siteConfig` object around line 440:

```javascript
const siteConfig = {
    // Personal Profile
    profile: {
        name: "Your Name",                    // ← Change this
        bio: "Your bio description...",       // ← Change this
        avatar: "images/hero/avatar.png"      // ← Avatar image path
    },

    // Text Sections
    textSections: {
        top: "First text section...",         // ← First paragraph
        bottom: "Second text section...",     // ← Second paragraph
        final: "Final text section..."        // ← Final paragraph
    },

    // Link Group 1 (after first gallery)
    linksGroup1: [
        {
            title: "Telegram",
            description: "Instant messaging",
            url: "https://t.me/yourusername",   // ← Change to your link
            image: "images/links/telegram.png"
        }
        // Add more links...
    ],

    // Gallery 1
    gallery1: [
        {
            image: "images/gallery/photo1.png",    // Image path
            description: "Photo description",       // Hover text
            link: "https://t.me/yourusername"       // ← Click destination
        }
        // Add more photos...
    ]
}
```

#### Method 2: Admin Panel
1. **Show Admin Button**: Press `Ctrl+Shift+A`
2. **Enter Password**: Default is `qwe5566@`
3. **Edit Content**: Modify content in the popup
4. **Save Changes**: Click save button

### 🖼️ Image Setup

#### Image Structure
```
images/
├── hero/           # Profile avatar
│   └── avatar.png  # 200x200px recommended
├── links/          # Social link icons
│   ├── telegram.png    # 100x100px recommended
│   ├── line.png
│   ├── instagram.png
│   └── wechat.png
├── gallery/        # First gallery
│   ├── photo1.png      # 500x500px+ recommended
│   ├── photo2.png
│   └── ... (up to 10)
└── gallery2/       # Second gallery
    ├── photo1.png
    ├── photo2.png
    └── ... (up to 10)
```

### 🌐 Deployment

#### GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → `main` branch
4. Your site will be live at `https://yourusername.github.io/korean-portfolio-pure-html/`

#### Netlify
1. Drag and drop the entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for automatic deployments

#### Traditional Web Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Set proper file permissions

#### IIS Server
1. Copy files to IIS website directory
2. Use the included `web.config` file
3. Ensure static file permissions are correct

### 🔧 Configuration

#### Change Admin Password
Find this line in `index.html` and modify:
```javascript
const adminPassword = "qwe5566@";  // ← Change to your password
```

#### Customize Colors
Find the CSS section and modify:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

#### Add More Links
Add new objects to `linksGroup1` or `linksGroup2`:
```javascript
{
    title: "New Platform",
    description: "Platform description",
    url: "https://yourlink.com",
    image: "images/links/youricon.png"
}
```

### 🛠️ Troubleshooting

**Q: Images not showing?**
A: Check that image paths are correct and files exist

**Q: How to add more links?**
A: Add new objects to the `linksGroup1` or `linksGroup2` arrays

**Q: How to change password?**
A: Find `const adminPassword = "qwe5566@";` in HTML and change it

**Q: Can I add more galleries?**
A: Yes, copy the gallery HTML/JS code and modify the IDs

---

## Chinese

### 🎯 项目简介

一个美观、完全独立的韩式风格个人链接页面，使用纯HTML、CSS和JavaScript构建。无需框架，无需依赖，直接打开即可使用！适用于社交媒体资料、个人品牌展示或作为着陆页。

### ✨ 功能特点

- 🚀 **零依赖**：纯HTML/CSS/JavaScript，无需任何框架
- 📱 **完全响应式**：在手机和电脑上都能完美显示
- 🎨 **韩式美学**：美丽的渐变背景和简洁设计
- 📸 **照片画廊**：两个可自定义的图片画廊，点击可跳转链接
- 🔗 **社交链接**：易于定制的社交媒体和联系方式链接
- ⚙️ **管理面板**：隐藏的管理界面，可实时编辑内容
- 💾 **本地存储**：更改保存在浏览器中，无需服务器
- 🌐 **多平台部署**：支持任何静态托管（GitHub Pages、Netlify等）
- 🔒 **密码保护**：安全的管理员访问，可自定义密码

### 🚀 快速开始

#### 方式一：下载ZIP包
1. [下载最新版本](https://github.com/nuomi8844/korean-portfolio-pure-html/archive/refs/heads/main.zip)
2. 解压并在浏览器中打开 `index.html`
3. 就这么简单！🎉

#### 方式二：克隆仓库
```bash
git clone https://github.com/nuomi8844/korean-portfolio-pure-html.git
cd korean-portfolio-pure-html
# 在浏览器中打开 index.html 或运行本地服务器
python -m http.server 8000  # Python 3
# 或者
npx serve .  # Node.js
```

### 📝 内容定制

#### 方法一：直接编辑HTML（推荐）
打开 `index.html` 文件，找到第440行左右的 `siteConfig` 对象：

```javascript
const siteConfig = {
    // 个人资料
    profile: {
        name: "你的名字",                    // ← 在这里修改
        bio: "个人简介描述...",               // ← 在这里修改
        avatar: "images/hero/avatar.png"     // ← 头像图片路径
    },

    // 文字内容
    textSections: {
        top: "第一段文字...",                // ← 第一段文字
        bottom: "第二段文字...",             // ← 第二段文字
        final: "最终文字..."                // ← 最后段文字
    },

    // 链接组1（第一个相册后）
    linksGroup1: [
        {
            title: "Telegram",
            description: "即时聊天",
            url: "https://t.me/你的用户名",    // ← 修改为你的链接
            image: "images/links/telegram.png"
        }
        // 添加更多链接...
    ],

    // 第一个相册
    gallery1: [
        {
            image: "images/gallery/photo1.png",    // 图片路径
            description: "图片描述",                // 悬停文字
            link: "https://t.me/你的用户名"         // ← 点击跳转链接
        }
        // 添加更多图片...
    ]
}
```

#### 方法二：使用管理面板
1. **显示管理按钮**：按 `Ctrl+Shift+A`
2. **输入密码**：默认密码是 `qwe5566@`
3. **编辑内容**：在弹出窗口中修改内容
4. **保存更改**：点击保存按钮

### 🖼️ 图片设置

#### 图片文件结构
```
images/
├── hero/           # 个人头像
│   └── avatar.png  # 建议200x200px
├── links/          # 社交链接图标
│   ├── telegram.png    # 建议100x100px
│   ├── line.png
│   ├── instagram.png
│   └── wechat.png
├── gallery/        # 第一个相册
│   ├── photo1.png      # 建议500x500px以上
│   ├── photo2.png
│   └── ... (最多10张)
└── gallery2/       # 第二个相册
    ├── photo1.png
    ├── photo2.png
    └── ... (最多10张)
```

### 🌐 部署方法

#### GitHub Pages
1. Fork 这个仓库
2. 进入 Settings → Pages
3. 选择 "Deploy from a branch" → `main` 分支
4. 你的网站将在 `https://你的用户名.github.io/korean-portfolio-pure-html/` 上线

#### Netlify
1. 将整个文件夹拖拽到 [Netlify Drop](https://app.netlify.com/drop)
2. 或连接你的GitHub仓库进行自动部署

#### 传统虚拟主机
1. 将所有文件上传到你的网站服务器
2. 确保 `index.html` 在根目录
3. 设置适当的文件权限

#### IIS服务器
1. 将文件复制到IIS网站目录
2. 使用包含的 `web.config` 文件
3. 确保静态文件权限正确

### 🔧 自定义配置

#### 修改管理密码
在 `index.html` 中找到这行并修改：
```javascript
const adminPassword = "qwe5566@";  // ← 修改为你的密码
```

#### 自定义颜色
找到CSS部分并修改：
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

#### 添加更多链接
在 `linksGroup1` 或 `linksGroup2` 中添加新对象：
```javascript
{
    title: "新平台",
    description: "平台描述",
    url: "https://你的链接.com",
    image: "images/links/你的图标.png"
}
```

### 🛠️ 常见问题

**问：图片不显示怎么办？**
答：检查图片路径是否正确，确保文件存在

**问：如何添加更多链接？**
答：在 `linksGroup1` 或 `linksGroup2` 数组中添加新对象

**问：如何修改密码？**
答：在HTML中找到 `const adminPassword = "qwe5566@";` 并修改

**问：可以添加更多相册吗？**
答：可以，复制相册的HTML/JS代码并修改ID

---

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### 💬 Support

If you encounter any issues:
1. Check the browser console for errors
2. Verify all file paths are correct
3. Ensure JavaScript is enabled in your browser

### 📞 Contact

- GitHub: [@nuomi8844](https://github.com/nuomi8844)
- Issues: [Report a bug](https://github.com/nuomi8844/korean-portfolio-pure-html/issues)

---

**Made with ❤️ for the Korean aesthetic community**