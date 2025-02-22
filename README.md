# Yichengliang

一个简单的个人网站项目，使用 HTML、CSS、JavaScript、jQuery、Bootstrap 等技术实现。

## 项目结构

Yichengliang/
├── css/ # 样式文件目录
│ ├── plugins/ # 插件样式文件
│ │ ├── bootstrap.min.css # Bootstrap 样式文件
│ │ ├── fancybox.min.css # Fancybox 弹出框样式文件
│ │ ├── font-awesome.min.css # Font Awesome 图标样式文件
│ │ ├── swiper.min.css # Swiper 轮播图样式文件
│ │ └── color-\*.css # 颜色主题样式文件
│ ├── webfonts/ # 字体文件目录
│ ├── files/ # 文件目录
│ └── img/ # 图片文件目录
├── js/ # JavaScript 文件目录
│ ├── plugins/ # 插件 JavaScript 文件
│ │ ├── animate.min.js # 动画效果 JavaScript 文件
│ │ ├── fancybox.min.js # Fancybox 弹出框 JavaScript 文件
│ │ ├── isotope.min.js # Isotope 网格布局 JavaScript 文件
│ │ ├── jquery.min.js # jQuery 库 JavaScript 文件
│ │ ├── overscroll.min.js # Overscroll 滚动效果 JavaScript 文件
│ │ ├── progressbar.min.js # 进度条 JavaScript 文件
│ │ ├── smooth-scrollbar.min.js # 平滑滚动条 JavaScript 文件
│ │ ├── swiper.min.js # Swiper 轮播图 JavaScript 文件
│ │ ├── swup.min.js # Swup 页面切换 JavaScript 文件
│ │ └── typing.min.js # 打字效果 JavaScript 文件
│ └── main.js # 主 JavaScript 文件
├── scss/ # SCSS 文件目录
│ ├── \_burger.scss # 汉堡按钮样式 SCSS 文件
│ ├── \_common.scss # 通用样式 SCSS 文件
│ └── \_config.scss # 配置样式 SCSS 文件
├── blog-2-col.html # 博客页面 HTML 文件
├── blog-3-col.html # 博客页面 HTML 文件
├── blog-post.html # 博客页面 HTML 文件
├── contact.html # 联系页面 HTML 文件
├── history.html # 历史页面 HTML 文件
├── onepage.html # 单页面 HTML 文件
├── portfolio-2-col.html # 作品页面 HTML 文件
├── portfolio-3-col.html # 作品页面 HTML 文件
├── README.md # 项目说明文档
└── index.html # 主入口 HTML 文件

## 功能特性

- 响应式设计：适配不同设备和屏幕尺寸，提供良好的用户体验。
- 动画效果：使用 CSS 和 JavaScript 实现各种动画效果，提升视觉体验。
- 轮播图：集成 Swiper 插件，实现图片和内容的轮播展示。
- 弹出框：使用 Fancybox 插件，实现图片和内容的弹出展示。
- 网格布局：使用 Isotope 插件，实现灵活的网格布局和筛选功能。
- 平滑滚动：集成 Smooth Scrollbar 插件，提供平滑的滚动效果。
- 进度条：使用 Progressbar 插件，展示动态进度条效果。
- 页面切换：集成 Swup 插件，实现无刷新页面切换效果。
- 打字效果：使用 Typing 插件，实现动态打字效果。
- 联系表单：集成联系表单，方便用户与网站所有者联系。
- 博客功能：提供博客页面，支持文章发布和展示。
- 作品展示：提供作品展示页面，支持多种布局方式。
- 历史页面：展示个人或项目的历史记录和时间轴。

## 快速开始

1. 克隆项目：

```bash
git clone https://github.com/effiy/yichengliang.git
```

2. 运行项目：

如果你希望在浏览器中自动刷新页面，可以考虑使用 browser-sync。以下是如何使用 browser-sync 的步骤：

1. 安装 browser-sync：

```bash
sudo npm install -g browser-sync
```

2. 使用 browser-sync 启动服务器并监视文件变化：

```bash
browser-sync start --server --files "*.html, *.css, *.js"
```
