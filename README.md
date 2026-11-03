# MiniChatLLM
极简学习项目：前后端 + LLM 对话工作台
目标：完整链路学习 FastAPI、同步/异步接口、数据库、日志、Docker、Git

## ✅ 项目覆盖知识点
- Git版本管理
- FastAPI 同步、异步接口开发
- SQLAlchemy 2.0 ORM（同步+异步会话）、SQLite
- 日志封装、全局异常处理
- Ollama / OpenAI兼容大模型调用
- 前端原生JS fetch、轮询查询异步任务
- Docker容器打包

## 📦 技术栈
后端：Python + FastAPI
ORM：SQLAlchemy 2.0
数据库：SQLite
前端：原生HTML + JS + Tailwind CDN
LLM：Ollama（本地大模型）

## 🚀 开发进度
- [x] 阶段0：项目初始化 & Git仓库
- [ ] 阶段1：FastAPI骨架 + 日志 + 环境配置
- [ ] 阶段2：数据库模型与CRUD
- [ ] 阶段3：同步对话接口
- [ ] 阶段4：异步任务接口
- [ ] 阶段5：前端页面联调
- [ ] 阶段6：异常和边界处理
- [ ] 阶段7：Docker打包

## 📝 运行前置
1. 安装 python >=3.10
2. 安装 ollama，拉取模型 ollama pull qwen2:1.5b
3. 复制 .env.example 为 .env，按需修改配置
