# 黑马智慧园区管理系统（vue-admin）

> 黑马程序员前端实战项目，基于 [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template) 二次开发的后台管理系统。

## 项目简介

本项目是一个智慧园区综合管理平台，涵盖园区内车辆出入、停车管理、物业管理、道路监控及系统配置等核心业务模块，为企业园区运营提供一站式的数字化管理解决方案。

## 技术栈

| 技术          | 说明                  |
| ------------- | --------------------- |
| Vue 2.6       | 前端渐进式框架        |
| Vue Router 3  | 路由管理              |
| Vuex 3        | 状态管理              |
| Element UI    | UI 组件库             |
| Axios         | HTTP 请求库           |
| Sass          | CSS 预处理器          |

## 功能模块

- **工作台** — 首页数据概览、快捷入口
- **车辆管理** — 园区车辆出入登记、车辆信息维护
- **园区管理** — 园区区域与车位管理
- **物业管理** — 物业费收缴、报修处理
- **道路管理** — 园区道路信息与监控
- **系统管理** — 用户、角色、权限配置

## 快速开始

```bash
# 克隆项目
git clone https://github.com/lmc-coder-dev/hmzs-project.git
```

```bash
# 进入项目目录
cd hmzs-project
```

```bash
# 安装依赖,node版本为16
npm install

# 启动开发服务器（默认端口 8081）
npm start

# 构建生产版本
npm run build
```

## 目录结构

```
src/
├── api/          # API 接口
├── assets/       # 静态资源（图片、图标）
├── components/   # 公共组件
├── constants/    # 常量定义
├── directive/    # 自定义指令
├── icons/        # SVG 图标
├── layout/       # 布局组件
├── router/       # 路由配置
├── store/        # Vuex 状态管理
├── styles/       # 全局样式
├── utils/        # 工具函数
├── views/        # 页面视图
│   ├── Car/      # 车辆管理
│   ├── Login/    # 登录页
│   ├── Park/     # 园区管理
│   ├── Property/ # 物业管理
│   ├── Rod/      # 道路管理
│   ├── System/   # 系统管理
│   └── Workbench/# 工作台
├── App.vue       # 根组件
└── main.js       # 入口文件
```

## License

MIT
