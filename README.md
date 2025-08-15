# WebNav Hub

一个现代化的新拟物化设计风格网站导航页面，提供快速访问常用网站的功能。

## 特性

- **新拟物化设计**: 采用深色主题和柔和阴影，营造出现代感和立体感
- **响应式布局**: 在各种设备上都能良好显示，包括桌面端和移动端
- **分类导航**: 将网站按类别组织，便于快速查找
- **平滑滚动**: 点击分类标签时平滑滚动到相应区域
- **返回顶部**: 向下滚动时自动显示返回顶部按钮
- **无依赖框架**: 纯 HTML、CSS 和 JavaScript 实现

## 设计亮点

1. **新拟物化风格**:
   - 深色背景 (#1E1E1E)
   - 双重阴影实现立体感（浅色高光 + 深色阴影）
   - 圆角设计 (20px)
   - 无明显边框，通过阴影创造立体效果

2. **交互效果**:
   - 按钮和卡片悬停时的阴影变化
   - 平滑的过渡动画
   - 返回顶部按钮动画效果

3. **响应式设计**:
   - 自适应不同屏幕尺寸
   - 移动端友好的布局调整

## 文件结构

```
.
├── index.html         # 主页面
├── style.css          # 样式文件
├── main.js            # 交互功能
└── README.md          # 项目说明文档
```

## 使用方法

1. 克隆或下载本项目
2. 在浏览器中打开 `index.html` 文件即可使用

## 自定义

### 添加新链接

在 `index.html` 文件中找到相应的分类区域，在 `links-grid` 容器内添加新的链接卡片：

```html
<a href="https://example.com" target="_blank" class="link-card">
  <i class="fa-solid fa-link link-icon"></i>
  <span class="link-name">网站名称</span>
</a>
```

### 修改样式

在 `style.css` 文件中可以修改颜色、阴影效果等样式：

```css
:root {
  /* 可以在这里修改主题颜色 */
  --primary-color: #4A90E2;
  --secondary-color: #50E3C2;
  --accent-color: #F5A623;
}
```

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 作者

WebNav Hub 由 [您的名字] 创建和维护

## 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - Inter 字体