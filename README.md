# 404 错误页面

一个美观、现代的 404 错误页面，具有自动跳转功能和可配置的变量。

## 功能特点

- 🎨 现代简洁的设计风格
- ⏰ 10秒倒计时自动跳转
- 🔄 手动返回首页按钮
- 📱 响应式设计，支持移动端
- ⚙️ 可配置的跳转地址和版权信息
- 🎭 精美的动画效果和交互体验

## 配置说明

### 快速配置

打开 `404.html` 文件，在 `<head>` 标签内找到配置区域，修改以下变量：

```javascript
// 跳转目标网址 - 修改为您的主页地址
const REDIRECT_URL = 'https://github.com/cola0908/Simple-404';

// 版权信息 - 修改为您的版权声明
const COPYRIGHT_INFO = 'COPYRIGHT © 2025 COLA_0908. ALL RIGHTS RESERVED.';
```

### 配置变量详解

#### REDIRECT_URL
- **类型**: 字符串
- **描述**: 设置用户点击"返回首页"按钮或倒计时结束后跳转的目标网址
- **示例**: 
  ```javascript
  const REDIRECT_URL = 'https://yourwebsite.com/';
  ```

#### COPYRIGHT_INFO
- **类型**: 字符串
- **描述**: 设置页面底部显示的版权信息
- **示例**: 
  ```javascript
  const COPYRIGHT_INFO = 'COPYRIGHT © 2025 您的网站名称. ALL RIGHTS RESERVED.';
  ```

## 使用方法

1. **下载文件**: 将 `404.html` 文件下载到您的项目中
2. **配置变量**: 按照上述说明修改配置变量
3. **部署使用**: 将文件上传到您的服务器，并配置 Web 服务器在遇到 404 错误时显示此页面


#### GitHub Pages
将文件命名为 `404.html` 并放在仓库根目录即可自动生效。

## 自定义样式

如果您需要进一步自定义页面样式，可以修改 `<style>` 标签内的 CSS 代码：

- **主色调**: 修改 `--primary-color` 和相关颜色变量
- **字体**: 修改 `font-family` 属性
- **动画**: 调整 `@keyframes` 动画效果
- **布局**: 修改容器的 `max-width`、`padding` 等属性

## 浏览器兼容性

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ 移动端浏览器

## 许可证

本项目采用 MIT 许可证，您可以自由使用、修改和分发。

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！
