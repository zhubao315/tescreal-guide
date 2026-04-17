# TESCREAL 完整指南

一个精美的静态网页，深入探索硅谷技术精英的隐秘世界观。

## 概述

TESCREAL 是一个由计算机科学家 Timnit Gebru 与哲学家 Émile Torres 于 2023 年提出的术语，用来描述硅谷及科技行业精英群体中盛行的一系列相互交织的技术乌托邦意识形态。

## 七大流派

| 字母 | 流派 | 英文 | 核心概念 |
|------|------|------|----------|
| **T** | 超人类主义 | Transhumanism | 通过技术超越人类限制 |
| **E** | 反熵主义 | Extropianism | 对抗熵增，追求无限进化 |
| **S** | 奇点主义 | Singularitarianism | 技术奇点与超智能 |
| **C** | 宇宙主义 | Cosmism | 星际文明与宇宙使命 |
| **R** | 理性主义 | Rationalism | 逻辑与证据优先 |
| **E** | 有效利他 | Effective Altruism | 最大化善意影响 |
| **A** | 长期主义 | Longtermism | 关注遥远未来 |

## 技术特性

- **响应式设计**：完美适配桌面端、移动端和平板设备
- **现代视觉效果**：星空背景、渐变动画、流畅过渡
- **交互式图表**：展示七大流派的内在联系
- **无障碍设计**：支持键盘导航和屏幕阅读器
- **高性能**：纯静态HTML，无依赖服务器

## 快速开始

### 本地预览

直接在浏览器中打开 `index.html` 文件即可查看。

或使用任意静态服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# PHP
php -S localhost:8000
```

然后访问 http://localhost:8000

### 部署到 GitHub Pages

1. Fork 或克隆此仓库
2. 进入仓库设置 (Settings)
3. 在 Pages 选项中选择 `main` 分支和 `/ (root)` 目录
4. 保存后等待几分钟，你的站点将上线

## 项目结构

```
tescreal-concept/
├── index.html    # 主页面（包含所有样式和脚本）
├── README.md     # 项目说明文档
└── LICENSE       # MIT 许可证
```

## 设计参考

- **字体**：Space Grotesk (标题)、Noto Sans SC (正文)、Cormorant Garamond (引用)
- **配色**：深空黑背景 + 七色流散（每个流派独特颜色）
- **动画**：AOS 动画库 + CSS 原生动画

## 浏览器兼容性

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 致谢

内容参考以下来源：

- [TESCREAL.org](https://tescreal.org/)
- [DAIR Institute - TESCREAL](https://www.dair-institute.org/projects/tescreal/)
- [Montreal Ethics Centre - TESCREAL Bundle](https://montrealethics.ai/the-tescreal-bundle/)
- 知乎专栏相关深度文章

## 许可证

MIT License - 欢迎自由使用和修改
