# 员工与部门管理系统 (Staff Manager)

这是一个基于 Django API 后端与 Angular 10 前端开发的高效、直观的员工与部门管理系统。系统支持部门信息的增删改查、员工档案的动态管理（包含照片上传功能），并使用轻量级的高性能 SQLite 数据库存储数据。

## 如何运行

### 1. 后端服务启动 (Django API)

进入后端项目目录，直接运行服务：
```bash
cd DjangoAPI
python start_api.py runserver
```
后端服务默认将运行在 `http://127.0.0.1:8000`。

### 2. 前端服务启动 (Angular 10)

进入前端项目目录，安装依赖并启动：
```bash
cd ui/angular10
npm install
npm start
```
前端服务默认将运行在 `http://localhost:4200`。
