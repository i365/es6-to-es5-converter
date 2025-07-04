[English](README_EN.md)
# ES6+ 转 ES5 转换器

## 简介

这是一个基于 Babel.js 的在线 JavaScript 语法转换工具，可以将现代 JavaScript 语法（ES6+）转换为传统的 ES5 语法，以确保在老旧浏览器中的兼容性。

🔗 **在线工具地址**: https://jstool.gitlab.io/es6-to-es5-converter/zh.html

## 主要功能

### 📁 文件处理
- **导入 JS 文件**: 支持拖拽上传、多文件选择或导入整个文件夹
- **批量转换**: 一次性处理多个 JS 文件
- **文件夹导入**: 支持导入整个文件夹，批量转换后下载 ZIP 文件，保持原有文件树结构和路径
- **下载功能**: 单文件下载或批量下载所有转换后的文件

### 💻 代码转换
- **实时转换**: 输入 JS 代码，实时转换为 ES5 语法
- **在线编译**: 基于 Babel.js 的在线编译工具
- **代码片段转换**: 支持函数语法转换和代码片段处理

### 🔧 语法支持

该工具支持以下现代 JavaScript 语法的转换：

- **箭头函数** → 普通函数
- **async/await** → Promise
- **解构赋值** 语法转换
- **模板字符串** 转换
- **let/const** → var
- **class类语法** 转换
- **ES6, ES7, ES8** 等新语法

## 使用场景

### 🌐 浏览器兼容性
- 解决新语法在老旧浏览器中的错误问题
- 兼容传统 Android 手机浏览器
- 兼容钉钉/微信内置浏览器
- 兼容嵌入式浏览器内核

### 📦 开发场景
- 无需 webpack、vite、Turbopack、Rspack 等构建工具的快速转换
- 开源 JS 库文件包含不支持的新语法时的快速解决方案
- 传统浏览器环境中的 JS 语法错误修复
- 批量压缩文件夹中的 JS 文件并转换语法

## 工具特点

- ✅ **零配置**: 无需复杂的构建工具配置
- ✅ **实时预览**: 即时查看转换结果
- ✅ **批量处理**: 支持大量文件的批量转换
- ✅ **文件结构保持**: 转换后保持原有的文件夹结构
- ✅ **多语言支持**: 支持中文、英文、西班牙文界面
- ✅ **错误提示**: 清晰的转换错误信息提示

## 如何使用

1. 访问 [ES6+ to ES5 转换器](https://jstool.gitlab.io/es6-to-es5-converter/zh.html)
2. 选择使用方式：
   - **文件上传**: 拖拽或选择 JS 文件/文件夹
   - **代码输入**: 直接在编辑器中输入 JS 代码
3. 等待自动转换完成
4. 下载转换后的文件或复制转换后的代码
