# Buct-Exp-Schedule-App

> 一个用于优雅展示北京化工大学实验课程表的静态 Web 应用。

## 📖 项目简介

`Buct-Exp-Schedule-App` 是一个基于 **Vue 3** + **Vite** 构建的轻量级静态网页应用，专为北京化工大学（BUCT）的学生设计。它能够以清晰、美观的方式呈现实验课程安排，支持按时间、课程等多维度浏览，帮助学生快速掌握实验课的时间、地点及注意事项。项目无需后端，所有数据均在前端处理，部署简单，开箱即用。

## ✨ 功能特性

- **实验课表可视化**：以卡片或时间轴形式展示实验课程，一目了然地查看每周实验安排。
- **最近排课提示**：自动高亮即将进行的实验课程，方便学生提前准备。
- **危险性提示**：针对涉及危险操作的实验，显示醒目的安全提示信息，保障实验安全。
- **PDF 资料引用**：支持关联实验指导书、PDF 文档等学习资料，点击即可快速查阅。
- **时间显示优化**：精确处理 `HH:mm` 格式的时间展示，确保时间信息准确无误。
- **响应式设计**：适配桌面端与移动端，随时随地查看课表。
- **静态部署**：纯前端实现，可轻松托管于 GitHub Pages、Vercel、Netlify 等平台。

## 🛠️ 技术栈

| 类别 | 技术 |
|------|------|
| 前端框架 | [Vue 3](https://vuejs.org/)（Composition API） |
| 构建工具 | [Vite](https://vitejs.dev/) |
| 语言 | [TypeScript](https://www.typescriptlang.org/) |
| 代码规范 | ESLint + Prettier |
| 类型检查 | `vue-tsc` |

> 项目基于 Vue 3 + Vite + TypeScript 的官方模板搭建，并使用 Volar 提供 `.vue` 文件的类型支持。

## 🚀 快速开始

### 环境要求

- [Node.js](https://nodejs.org/)（建议 v18 或更高版本）
- npm 或 yarn / pnpm

### 安装依赖

```bash
npm install
```

### 开发模式（热重载）

```bash
npm run dev
```

启动后访问 `http://localhost:5173` 即可预览应用。

### 生产构建

```bash
npm run build
```

构建产物默认输出至 `dist/` 目录，可直接部署到任意静态服务器。

## 📁 项目结构

```
Buct-Exp-Schedule-App/
├── public/                 # 静态资源（图标、PDF 资料等）
├── src/
│   ├── assets/             # 样式、图片等资源
│   ├── components/         # Vue 组件
│   ├── core/               # 核心逻辑与数据处理
│   ├── App.vue             # 根组件
│   └── main.ts             # 应用入口
├── .eslintrc.cjs           # ESLint 配置
├── .prettierrc.json        # Prettier 配置
├── package.json
├── vite.config.ts
└── README.md
```

## 🔧 配置与自定义

- **Vite 配置**：参见 [Vite Configuration Reference](https://vitejs.dev/config/)。
- **IDE 推荐**：使用 [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) 扩展，以获得完整的 TypeScript 和模板支持。
- **实验数据**：课程数据通常维护于 `src/core/` 或 `src/assets/` 下的数据文件中，可按实际排课情况更新。

## 📄 许可证

本项目采用 [MIT License](https://opensource.org/licenses/MIT) 开源协议（如未另行指定，请以仓库内 `LICENSE` 文件为准）。

## 🙏 致谢

感谢所有为北京化工大学实验教学信息化建设做出贡献的老师和同学。如果你在使用中发现任何问题或有改进建议，欢迎提交 [Issue](https://github.com/SnowmanGao/Buct-Exp-Schedule-App/issues) 或 [Pull Request](https://github.com/SnowmanGao/Buct-Exp-Schedule-App/pulls)。

---

**Buct-Exp-Schedule-App** — 让实验课表更清晰，让学习安排更从容。
