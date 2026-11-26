# Hachile Tools

<div align="center"><img alt="部署：GitHub Pages" src="https://img.shields.io/badge/deploy-GitHub%20Pages-blue"> <img alt="许可证：MIT" src="https://img.shields.io/badge/license-MIT-green"> <img alt="语言：HTML、CSS 与 JavaScript" src="https://img.shields.io/badge/language-HTML%20%2F%20CSS%20%2F%20JS-orange"></div>

[打开 Hachile Tools](https://tools.hachile.org/)

- [收录内容](#收录内容)
- [本地预览](#本地预览)
- [目录维护](#目录维护)
- [许可证](#许可证)

## 收录内容

Hachile Tools 是一个常用网站与项目导航，包含同济校园、编程与 AI、论文与科研、办公与生活、地图与网络五个栏目。站内搜索按名称、用途或网址实时筛选卡片，清空关键词即可恢复完整目录。

## 本地预览

网站使用静态 HTML、CSS 和原生 JavaScript，无需安装依赖或构建。在仓库根目录启动服务器：

```sh
python -m http.server 8000
```

然后打开 [本地预览](http://localhost:8000/)。

## 目录维护

| 文件 | 用途 |
| --- | --- |
| `index.html` | 栏目、链接卡片和站内搜索 |
| `style.css` | 导航、卡片、响应式布局及亮暗主题 |
| `CNAME` | GitHub Pages 自定义域名 |

提交新资源时，在对应栏目添加卡片，提供网址和简短用途，并检查重复链接。新增栏目时，同步更新侧边栏和顶部导航。

## 许可证

本站代码与文档采用 [MIT 许可证](LICENSE)。外链内容遵循各站点和项目各自的许可证或使用条款。
