# 🔧 Web Tools

<div align="center">
  <img src="https://img.shields.io/badge/Tools-Collection-blue?style=for-the-badge&logo=tools&logoColor=white" alt="Tools Collection">
  <img src="https://img.shields.io/badge/Language-HTML%20%7C%20CSS%20%7C%20JavaScript-orange?style=for-the-badge&logo=html5&logoColor=white" alt="Languages">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Status">
</div>

<div align="center">
  <h3>🌟 实用网页工具集合 🌟</h3>
  <p>免费开源 · 即开即用 · 无需安装</p>
</div>

---

## 📖 简介

这是一个实用的网页工具集合项目，采用纯前端技术开发，无需后端服务器，可以直接在浏览器中使用。所有工具都具有现代化的界面设计和良好的用户体验。

## 🛠️ 当前工具

### 🔗 智能网盘直链转换器

**功能描述**: 将主流网盘的分享链接转换为直接下载链接

**支持平台**:
- ✅ Google Drive
- ✅ OneDrive
- ✅ Dropbox
- ⚠️ 百度网盘（识别提示）
- ⚠️ 蓝奏云（识别提示）

**功能特点**:
- 🤖 自动识别网盘类型
- 📋 一键复制转换结果
- ⌨️ 支持回车键快速转换
- 📱 响应式设计，移动端友好
- 🎨 现代化UI界面

## 🚀 快速开始

### 方法一：直接使用（推荐）
直接打开 `cloud-link-converter/index.html` 文件即可在浏览器中使用。

### 方法二：本地HTTP服务器运行
```bash
# 克隆仓库
git clone https://github.com/your-username/web-tools.git

# 进入项目目录
cd web-tools

# 使用任意HTTP服务器运行，例如：
# 使用Python
python -m http.server 8000

# 使用Node.js
npx http-server

# 使用Live Server（VS Code插件）
# 右键点击 cloud-link-converter/index.html -> Open with Live Server
```

### 方法三：部署到服务器
1. 将整个项目文件夹上传到Web服务器
2. 通过浏览器访问对应的HTML文件

## 📁 项目结构

```
web-tools/
├── README.md                   # 项目说明文件
└── cloud-link-converter/       # 智能网盘直链转换器
    └── index.html              # 转换器主页面
```

## 🎯 使用指南

### 智能网盘直链转换器

**使用步骤：**
1. 打开 `cloud-link-converter/index.html`
2. 复制网盘分享链接
3. 粘贴到输入框中
4. 点击"智能转换"按钮或按回车键
5. 复制生成的直链

**操作技巧：**
- 支持自动粘贴功能
- 支持回车键快速转换
- 自动识别网盘类型
- 一键复制转换结果

## 🔧 技术栈

- **前端技术**: HTML5 + CSS3 + JavaScript
- **样式特性**:
  - CSS Grid 和 Flexbox 布局
  - CSS 动画和过渡效果
  - 响应式设计（Media Queries）
- **JavaScript功能**:
  - 正则表达式匹配
  - DOM操作
  - 事件处理
- **兼容性**: 支持现代浏览器（Chrome、Firefox、Safari、Edge）

## 📦 部署指南

### GitHub Pages
1. Fork 这个仓库
2. 进入仓库设置页面
3. 找到 "Pages" 设置
4. 选择 "Deploy from a branch"
5. 选择 "main" 分支
6. 保存设置，获得访问链接

### Cloudflare Pages
1. Fork 这个仓库
2. 登录 [Cloudflare Pages](https://pages.cloudflare.com)
3. 连接你的GitHub账户
4. 选择Fork的仓库
5. 部署完成，获得访问链接

### Vercel
1. 登录 [Vercel](https://vercel.com)
2. 点击 "New Project"
3. 导入GitHub仓库
4. 部署完成

### 其他静态托管平台
由于项目是纯静态文件，可以部署到任何支持静态网站的平台。

## 🚀 未来规划

计划添加更多实用工具：

### 🎨 设计工具
- 颜色选择器
- 渐变生成器
- 图标生成器

### 🔧 开发工具
- JSON格式化器
- Base64编解码
- URL编解码
- 正则表达式测试器

### 📊 数据工具
- CSV转换器
- 二维码生成器
- 文本处理工具

## 🤝 贡献指南

欢迎贡献新的工具或改进现有工具！

### 如何贡献

1. **Fork** 这个仓库
2. 创建你的功能分支 (`git checkout -b feature/NewTool`)
3. 提交你的改动 (`git commit -m 'Add new tool'`)
4. 推送到分支 (`git push origin feature/NewTool`)
5. 打开一个 **Pull Request**

### 贡献规范

- 保持代码风格一致
- 添加必要的注释
- 确保工具在主流浏览器中正常工作
- 提供清晰的使用说明
- 采用响应式设计

## 📞 问题反馈

如果你发现任何问题或有改进建议，欢迎通过以下方式反馈：

- 💬 [GitHub Issues](https://github.com/your-username/web-tools/issues)
- 📧 提交问题报告

## ✨ 特色功能

- **🎯 即开即用**: 无需安装，打开网页即可使用
- **🎨 现代设计**: 采用现代化UI设计，美观易用
- **📱 响应式**: 完美适配桌面端和移动端
- **🔒 隐私安全**: 纯前端处理，数据不经过服务器
- **🚀 高性能**: 优化的代码，快速响应

## 🌟 支持项目

如果这个项目对你有帮助，请给个 ⭐️ Star！

你也可以通过以下方式支持项目：
- 🔗 分享给朋友
- 📝 提交Bug报告
- 💡 建议新功能
- 🤝 贡献代码

---

<div align="center">
  <p>Made with ❤️ | © 2025 Web Tools</p>
  <p>🚀 持续更新中，敬请期待更多实用工具！</p>
</div>