# 个人网站

一个功能完整、视觉吸引力强的个人网站，包含个人简介、专业技能展示、项目作品集、联系方式等核心板块。

## 技术栈

- HTML5
- CSS3
- JavaScript
- Tailwind CSS (CDN)
- Font Awesome (CDN)

## 文件结构

```
MyWeb/
├── index.html          # 主页面
└── README.md           # 项目说明文档
```

## 功能特点

- 响应式设计，适配桌面端、平板和移动设备
- 现代美观的视觉设计
- 流畅的交互动画效果
- 完整的导航系统
- 个人简介和专业技能展示
- 项目作品集展示
- 联系方式和表单
- 社交媒体链接

## 部署步骤

### 1. 本地开发

1. 克隆或下载本项目到本地
2. 打开 `index.html` 文件即可在浏览器中查看

### 2. 部署到静态网站托管服务

#### 选项 1: GitHub Pages

1. 在 GitHub 上创建一个新仓库
2. 将项目文件推送到仓库
3. 在仓库设置中启用 GitHub Pages
4. 选择 `main` 分支作为源
5. 等待几分钟，网站将在 `https://[username].github.io/[repository-name]` 上可用

#### 选项 2: Vercel

1. 访问 [Vercel](https://vercel.com/)
2. 使用 GitHub 账号登录
3. 导入你的 GitHub 仓库
4. 点击 "Deploy" 按钮
5. 等待部署完成，Vercel 将提供一个唯一的域名

#### 选项 3: Netlify

1. 访问 [Netlify](https://www.netlify.com/)
2. 使用 GitHub 账号登录
3. 点击 "New site from Git"
4. 选择你的 GitHub 仓库
5. 点击 "Deploy site"
6. 等待部署完成，Netlify 将提供一个唯一的域名

## 上线后的网站链接

部署完成后，你的网站将可以通过以下方式访问：

- GitHub Pages: `https://[username].github.io/[repository-name]`
- Vercel: `https://[project-name].vercel.app`
- Netlify: `https://[random-name].netlify.app`

## 自定义指南

1. **修改个人信息**：在 `index.html` 文件中修改个人简介、联系方式等信息
2. **更换图片**：替换 `img` 标签中的图片链接
3. **调整颜色方案**：修改 `tailwind.config` 中的颜色配置
4. **添加/修改项目**：在 `projects` 部分添加或修改项目卡片
5. **添加/修改技能**：在 `skills` 部分添加或修改技能卡片

## 响应式测试

网站已经通过以下设备的响应式测试：

- 桌面端 (1920px × 1080px)
- 平板 (768px × 1024px)
- 移动设备 (375px × 667px)

## 性能优化

- 使用 Tailwind CSS CDN 减少文件大小
- 优化图片加载
- 减少 JavaScript 执行时间
- 使用 CSS 过渡代替 JavaScript 动画

## 浏览器兼容性

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可证

MIT License
