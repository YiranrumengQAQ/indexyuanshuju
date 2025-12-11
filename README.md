# 🗑️ 元数据清除工具

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

一个功能强大的浏览器端图片和视频元数据清除工具，可以安全地删除 EXIF、GPS 定位等隐私敏感信息。

[在线演示](https://your-demo-link.com) | [报告问题](https://github.com/yourusername/metadata-cleaner/issues) | [功能建议](https://github.com/yourusername/metadata-cleaner/issues/new)

---

## ✨ 主要特性

- 🔒 **隐私优先** - 所有处理在浏览器本地完成，文件不会上传到服务器
- 🔍 **元数据检测** - 自动识别并显示 EXIF、GPS 定位、设备信息等元数据
- 🖼️ **多格式支持** - 支持 JPG、PNG、GIF、WebP、MP4、WebM、MOV 等主流格式
- ⚡ **快速处理** - 采用 Canvas 技术快速处理，保持高质量输出
- 🎨 **现代设计** - 精美的用户界面，流畅的动画效果
- 📱 **响应式布局** - 完美支持桌面和移动设备
- 🌿 **清新主题** - 绿色自然风格的视觉设计
- 🔐 **验证码保护** - 集成数学验证码，防止滥用

---

## 🚀 快速开始

### 在线使用

直接访问在线演示地址，无需安装任何软件。

### 本地部署

1. **克隆仓库**
   ```bash
   git clone https://github.com/yourusername/metadata-cleaner.git
   cd metadata-cleaner
   ```

2. **打开文件**
   
   直接在浏览器中打开 `index.html` 文件即可使用。

3. **或使用本地服务器**（推荐）
   ```bash
   # 使用 Python
   python -m http.server 8000
   
   # 或使用 Node.js
   npx http-server
   ```
   
   然后访问 `http://localhost:8000`

---

## 📖 使用指南

### 基本操作

1. **上传文件**
   - 点击上传区域选择文件
   - 或直接拖拽文件到上传区域

2. **查看元数据**
   - 上传后自动显示检测到的元数据信息
   - 包括 GPS 定位、拍摄设备、拍摄时间等

3. **清除元数据**
   - 点击"清除元数据"按钮
   - 完成验证码验证
   - 等待处理完成

4. **下载文件**
   - 处理完成后点击"下载文件"按钮
   - 下载的文件已移除所有元数据

### 支持的文件格式

#### 图片格式
- JPG/JPEG
- PNG
- GIF
- WebP

#### 视频格式
- MP4
- WebM
- MOV

---

## 🛡️ 隐私保护

### 可检测和清除的元数据

- **设备信息**: 制造商、型号
- **时间信息**: 拍摄时间、修改时间
- **GPS 信息**: 经纬度、海拔高度
- **相机参数**: 光圈、快门、ISO、焦距
- **软件信息**: 编辑软件、版本
- **版权信息**: 作者、版权声明
- **其他信息**: 用户注释、白平衡等

### 安全性说明

✅ **完全本地处理** - 所有操作在您的浏览器中完成  
✅ **零数据上传** - 文件不会发送到任何服务器  
✅ **开源透明** - 代码完全开源，可审计  
✅ **即用即走** - 无需注册，无需安装  

---

## 🔧 技术栈

- **前端框架**: 纯原生 HTML5 + CSS3 + JavaScript
- **图片处理**: Canvas API
- **元数据读取**: [EXIF.js](https://github.com/exif-js/exif-js)
- **验证码服务**: xxapi.cn Chinese Captcha API
- **设计风格**: 现代扁平化 + 绿色自然主题

---

## 🎨 界面预览

### 主界面
- 清新的绿色自然风格
- 拖拽上传支持
- 实时预览功能

### 元数据展示
- 网格化布局
- 详细的元数据信息
- GPS 定位警告提示

### 处理进度
- 实时进度条
- 动画加载效果
- 处理状态反馈

---

## 📝 开发说明

### 项目结构

```
metadata-cleaner/
│
├── index.html          # 主页面文件（包含所有代码）
├── README.md           # 项目说明文档
└── LICENSE             # 开源协议
```

### 代码特点

- **单文件应用** - 所有代码集成在一个 HTML 文件中
- **模块化设计** - 清晰的功能分离和状态管理
- **错误处理** - 完善的异常捕获和用户提示
- **性能优化** - 高效的图片处理算法
- **可访问性** - 支持键盘操作和屏幕阅读器

### 自定义配置

可以修改 CSS 变量来自定义主题颜色：

```css
:root {
    --primary-green: #2d5016;
    --secondary-green: #3d6b25;
    --light-green: #5a8c37;
    --accent-green: #7fb069;
    --cream-white: #fffef7;
    /* ... 更多颜色变量 */
}
```

---

## 🤝 贡献指南

欢迎贡献代码、报告问题或提出建议！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 开发建议

- 保持代码风格一致
- 添加必要的注释
- 测试新功能的兼容性
- 更新相关文档

---

## 📋 待办事项

- [ ] 支持批量处理多个文件
- [ ] 添加更多图片格式支持（TIFF、RAW）
- [ ] 实现自定义元数据删除选项
- [ ] 添加元数据对比功能
- [ ] 支持 PWA 离线使用
- [ ] 添加多语言支持
- [ ] 优化视频处理性能

---

## ⚠️ 注意事项

1. **浏览器兼容性**
   - 推荐使用 Chrome、Firefox、Safari 或 Edge 最新版本
   - 需要支持 HTML5 Canvas API

2. **文件大小限制**
   - 建议处理 50MB 以内的文件
   - 大文件可能导致浏览器卡顿

3. **视频处理说明**
   - 视频处理仅复制文件内容，不重新编码
   - 某些视频格式的元数据可能无法完全清除

4. **验证码说明**
   - 验证码依赖第三方 API 服务
   - 网络不佳时可能加载失败

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

---

## 🙏 致谢

- [EXIF.js](https://github.com/exif-js/exif-js) - EXIF 元数据读取库
- [xxapi.cn](https://xxapi.cn) - 验证码 API 服务
- 所有为本项目贡献代码和建议的开发者

---

## 📞 联系方式

- 作者: Your Name
- 邮箱: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- 问题反馈: [Issues](https://github.com/yourusername/metadata-cleaner/issues)

---

## ⭐ Star History

如果这个项目对你有帮助，请给它一个 ⭐ Star！

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/metadata-cleaner&type=Date)](https://star-history.com/#yourusername/metadata-cleaner&Date)

---

<div align="center">

**[⬆ 回到顶部](#-元数据清除工具)**

Made with ❤️ and 🌿

</div>
