# 简易任务管理看板
> 基于 Vite + TypeScript 开发的前端任务管理项目

## 项目介绍
学习工程化项目搭建，使用TS做类型约束，拆分目录结构，实现任务的增删改查与本地存储。

## 技术栈
- TypeScript
- Vite
- CSS3

## 目录结构
task/
├─ index.html          # 入口页面
├─ src/
│  ├─ main.ts          # 入口 ts
│  ├─ types/           # TS 类型定义
│  ├─ utils/           # 工具函数
│  ├─ api/             # 模拟接口
│  └─ css/             # 样式文件
├─ tsconfig.json       # TS 配置
├─ package.json        # 项目配置
├─ .gitignore          # git 忽略文件
└─ README.md           # 项目说明


## 运行项目
```bash
# 安装依赖
npm install

# 启动开发服务
npm run dev

# 打包构建
npm run build
