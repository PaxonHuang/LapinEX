# LapinEX 计算机社团网站

这是一个基于Hexo框架和Butterfly主题的大学计算机社团官方网站。

## 项目介绍

LapinEX计算机社团网站是为大学计算机社团设计的官方网站，提供社团信息、活动公告、技术博客、项目展示等功能。网站采用现代化设计，响应式布局，支持多种设备访问。

## 技术栈

- [Hexo](https://hexo.io/)：静态网站生成框架
- [Butterfly](https://butterfly.js.org/)：美观、功能丰富的Hexo主题
- [GitHub Pages](https://pages.github.com/)：网站托管平台

## 功能特点

- 响应式设计，适配各种设备
- 社团介绍、团队成员展示
- 技术博客文章发布
- 项目作品展示
- 招新信息发布
- 保研和就业指南
- 站内搜索功能
- 评论互动系统

## 本地开发

### 环境要求

- Node.js (>= 12.0.0)
- Git

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/PaxonHuang/LapinEX.git
cd LapinEX
```

2. 安装依赖
```bash
npm install
```

3. 本地预览
```bash
npm run server
```

4. 生成静态文件
```bash
npm run build
```

5. 部署到GitHub Pages
```bash
npm run deploy
```

## 目录结构

```
LapinEX/
├── _config.yml          # Hexo配置文件
├── _config.butterfly.yml # Butterfly主题配置文件
├── package.json         # 项目依赖
├── scaffolds/           # 模板文件夹
├── source/              # 源文件
│   ├── _posts/          # 博客文章
│   ├── about/           # 关于页面
│   ├── contact/         # 联系页面
│   ├── projects/        # 项目页面
│   ├── teams/           # 团队页面
│   ├── jobs/            # 招新页面
│   ├── graduate/        # 保研页面
│   ├── career/          # 就业页面
│   └── img/             # 图片资源
└── themes/              # 主题文件夹（由npm安装）
```

## 贡献指南

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开一个 Pull Request

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 联系方式

- 项目维护者：LapinEX团队
- 邮箱：contact@lapinex.com
- GitHub：[https://github.com/PaxonHuang/LapinEX](https://github.com/PaxonHuang/LapinEX)