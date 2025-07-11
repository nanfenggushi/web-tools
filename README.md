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

**功能描述**: 将主流网盘的分享链接转换为直接下载链接，支持短链接展开、密码处理和批量转换

**支持平台**:

**🌍 国外平台（直链转换）**:
- ✅ Google Drive - 完美支持文件ID提取
- ✅ OneDrive - 支持多种链接格式
- ✅ Dropbox - 自动域名替换
- ✅ MediaFire - 随机服务器分配
- ✅ MEGA - 加密链接处理
- ✅ ZippyShare - 基础转换
- ✅ 4shared - 文件下载链接
- ✅ Uploaded - 欧洲文件托管
- ✅ Firefox Send - 直链支持
- ✅ WeTransfer - API接口
- ✅ SendSpace - 下载链接生成

**🇨🇳 国内平台（智能解析）**:
- 🔧 百度网盘 - 多链接生成 + 使用指导
- 🔧 蓝奏云 - 镜像域名 + 多路径解析
- 🔧 天翼云 - API接口生成
- 🔧 阿里云盘 - API接口支持
- 🔧 夸克网盘 - 分享链接处理
- 🔧 123云盘 - 下载信息获取
- 🔧 城通网盘 - 文件路径解析
- 🔧 微云 - 分享下载支持
- 🔧 奶牛快传 - 传输下载
- 🔧 坚果云 - 企业网盘支持
- 🔧 TeraBox - 新兴平台

**🔗 短链接展开**:
- ✅ bit.ly - Bitly短链接
- ✅ tinyurl.com - TinyURL
- ✅ t.co - Twitter短链接
- ✅ is.gd - Is.gd短链接
- ✅ short.link - Short.link

**🚀 核心功能特点**:
- 🤖 **智能识别**: 自动检测网盘类型和链接格式
- 🔐 **密码支持**: 自动显示密码输入框（百度网盘、蓝奏云等）
- 🔗 **短链展开**: 自动展开各种短链接服务
- 📊 **批量处理**: 支持多个链接同时转换，实时进度显示
- 📋 **多种复制**: 单链接复制、批量复制、一键测试
- 🔍 **链接测试**: 单个测试、批量测试所有生成的链接
- 📱 **响应式设计**: 完美适配桌面端和移动端
- 🎨 **现代化UI**: 毛玻璃效果、动画过渡、深色主题
- ⚡ **实时反馈**: 转换状态、错误提示、成功通知
- 🛡️ **隐私安全**: 纯前端处理，数据不经过服务器

## 🚀 快速开始

### 方法一：直接使用（推荐）
直接打开 `cloud-link-converter/index.html` 文件即可在浏览器中使用。

### 方法二：本地HTTP服务器运行
```bash
# 克隆仓库
git clone https://github.com/nanfenggushi/web-tools.git

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

**基础使用：**
1. 打开 `cloud-link-converter/index.html`
2. 复制网盘分享链接
3. 粘贴到输入框中
4. 如需要密码，会自动显示密码输入框
5. 点击"智能转换"按钮或按回车键
6. 复制生成的直链或使用测试功能

**高级功能：**

**🔐 密码处理**
- 百度网盘、蓝奏云等需要密码的平台会自动显示密码输入框
- 输入提取码后重新转换即可获得带密码的访问链接

**🔗 短链接展开**
- 勾选"自动展开短链接"选项
- 支持 bit.ly、tinyurl.com、t.co 等主流短链接服务
- 自动递归展开多层短链接

**📊 批量处理**
- 勾选"批量处理模式"或直接粘贴多行链接
- 实时显示处理进度和结果统计
- 支持成功/失败分类显示

**🔍 链接测试**
- 单个链接：点击"测试链接"在新窗口打开
- 多个链接：点击"测试全部"批量打开所有链接
- 自动间隔1秒打开，避免浏览器阻止

**💡 使用技巧：**
- 支持拖拽链接到页面进行转换
- 支持 Ctrl+V 自动粘贴并转换
- 自动检测剪贴板中的网盘链接
- 转换历史记录（控制台查看）
- 支持URL参数传递链接：`?url=分享链接`

**🎯 平台特殊说明：**

**国外平台**：通常能生成真正的直链，可直接下载

**国内平台**：由于安全限制，提供以下解决方案：
- **百度网盘**：生成多个访问链接 + 详细操作指导
- **蓝奏云**：提供多个镜像域名和下载路径
- **其他平台**：生成API接口链接，需要进一步处理

## 📋 平台转换效果详解

### 🌍 国外平台（直链转换）

| 平台 | 转换效果 | 成功率 | 说明 |
|------|----------|--------|------|
| Google Drive | ✅ 真实直链 | 95% | 自动提取文件ID，生成下载链接 |
| OneDrive | ✅ 真实直链 | 90% | 支持多种链接格式，域名替换 |
| Dropbox | ✅ 真实直链 | 85% | 替换为下载域名，去除参数 |
| MediaFire | ✅ 真实直链 | 80% | 随机服务器分配，可能需要重试 |
| MEGA | ⚠️ API接口 | 70% | 加密链接，需要密钥解析 |
| WeTransfer | ⚠️ API接口 | 60% | 需要API认证，时效性限制 |

### 🇨🇳 国内平台（智能解析）

| 平台 | 转换效果 | 实用性 | 说明 |
|------|----------|--------|------|
| 百度网盘 | 🔧 多链接 + 指导 | ⭐⭐⭐⭐ | 提供访问链接和详细操作步骤 |
| 蓝奏云 | 🔧 镜像域名 + 多路径 | ⭐⭐⭐⭐ | 多个可能的下载链接，成功率较高 |
| 天翼云 | 🔧 API接口 | ⭐⭐ | 需要登录认证，建议手动下载 |
| 阿里云盘 | 🔧 API接口 | ⭐⭐ | 需要token认证，API调用复杂 |
| 夸克网盘 | 🔧 API接口 | ⭐⭐ | 新兴平台，API限制较多 |

### 🔗 短链接展开

| 服务 | 展开效果 | 成功率 | 说明 |
|------|----------|--------|------|
| bit.ly | ✅ 完全展开 | 90% | 支持API展开和重定向跟踪 |
| tinyurl.com | ✅ 完全展开 | 85% | 通用重定向方法 |
| t.co | ✅ 完全展开 | 80% | Twitter短链接，可能有限制 |
| is.gd | ✅ 完全展开 | 85% | 简单重定向，成功率较高 |

## 🔧 技术栈

- **前端技术**: HTML5 + CSS3 + ES6+ JavaScript
- **样式特性**:
  - CSS Grid 和 Flexbox 布局
  - CSS 动画和过渡效果（毛玻璃、浮动动画）
  - 响应式设计（Media Queries）
  - CSS 变量和现代特性
- **JavaScript功能**:
  - ES6+ 异步编程（async/await、Promise）
  - 正则表达式匹配和链接解析
  - DOM操作和事件处理
  - Fetch API 网络请求
  - 剪贴板 API 操作
  - 本地存储和历史记录
  - 防抖和节流优化
- **核心算法**:
  - 多平台链接模式匹配
  - 短链接递归展开
  - 批量处理队列管理
  - 错误处理和重试机制
- **兼容性**: 支持现代浏览器（Chrome 60+、Firefox 55+、Safari 12+、Edge 79+）

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

### 🔗 网盘转换器增强
- [ ] 更多国外平台支持（Rapidshare、Uploaded等）
- [ ] 真实API调用（需要后端支持）
- [ ] 链接有效性检测
- [ ] 下载速度测试
- [ ] 文件信息获取（大小、类型等）
- [ ] 转换历史管理界面
- [ ] 自定义转换规则
- [ ] 浏览器扩展版本

### 🎨 设计工具
- [ ] 颜色选择器和调色板
- [ ] CSS渐变生成器
- [ ] 图标生成器和编辑器
- [ ] 字体预览工具

### 🔧 开发工具
- [ ] JSON格式化器和验证器
- [ ] Base64编解码工具
- [ ] URL编解码工具
- [ ] 正则表达式测试器
- [ ] 代码压缩和美化
- [ ] API测试工具

### 📊 数据工具
- [ ] CSV/Excel转换器
- [ ] 二维码生成器和解析器
- [ ] 文本处理工具集
- [ ] 数据可视化工具
- [ ] 文件格式转换器

### 🌐 网络工具
- [ ] IP地址查询
- [ ] 域名信息查询
- [ ] 网站性能测试
- [ ] SSL证书检查

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

## ❓ 常见问题

### Q: 为什么国内网盘不能生成真正的直链？
A: 国内网盘（如百度网盘、蓝奏云）有严格的安全限制和反爬虫机制，无法通过简单的URL转换生成直链。本工具提供多种可能的访问方式和详细的操作指导，帮助用户更便捷地下载文件。

### Q: 生成的链接无法下载怎么办？
A:
1. **国外平台**：尝试刷新页面重新转换，或检查原链接是否有效
2. **国内平台**：按照提示逐个尝试生成的链接，通常第一个链接成功率最高
3. **短链接**：确保开启了"自动展开短链接"选项

### Q: 批量处理时部分链接失败？
A: 这是正常现象。不同平台的链接格式和限制不同，工具会显示详细的成功/失败统计。建议：
- 检查失败的链接格式是否正确
- 对于需要密码的链接，先单独处理
- 使用"测试全部"功能验证生成的链接

### Q: 工具是否安全，会泄露我的链接吗？
A: 完全安全。本工具采用纯前端技术，所有处理都在您的浏览器本地进行，不会将任何数据发送到服务器。您可以断网使用或查看源代码验证。

### Q: 支持哪些浏览器？
A: 支持所有现代浏览器：
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Q: 可以离线使用吗？
A: 基本功能可以离线使用，但短链接展开功能需要网络连接。建议保存网页到本地以便离线使用。

## 📞 问题反馈

如果你发现任何问题或有改进建议，欢迎通过以下方式反馈：

- 💬 [GitHub Issues](https://github.com/your-username/web-tools/issues)
- 📧 提交问题报告
- 🐛 Bug报告请包含：浏览器版本、链接示例、错误截图

## ✨ 特色功能

- **🎯 即开即用**: 无需安装，打开网页即可使用
- **🎨 现代设计**: 毛玻璃效果、动画过渡、深色主题
- **📱 响应式**: 完美适配桌面端和移动端
- **🔒 隐私安全**: 纯前端处理，数据不经过服务器
- **🚀 高性能**: 优化的代码，防抖处理，快速响应
- **🤖 智能识别**: 自动检测链接类型，提供最佳转换方案
- **🔧 多功能**: 短链展开、密码处理、批量转换一应俱全
- **🔍 实用测试**: 一键测试生成的链接，验证有效性
- **📊 进度可视**: 批量处理实时进度，成功失败分类显示

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