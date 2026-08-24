<div align="center">

# 👋 你好，我是 Ruifeng

### AI 全栈开发 · Python 后端 · LLM 应用工程

专注于将 **大模型能力真正落地为可用产品**

`Python` · `FastAPI` · `Vue 3` · `TypeScript` · `PostgreSQL` · `RAG` · `Agent` · `Docker`

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=fengfeng-666\&label=Profile%20Views\&style=flat)

</div>

---

## 👨‍💻 关于我

我是计算机科学与技术专业学生，目前主要专注于 **AI 应用开发与全栈工程实践**。

相比单纯调用大模型 API，我更关注如何把 LLM 能力真正接入业务系统，包括：

* 🤖 **AI 应用**：LLM、RAG、Agent、多智能体、多模态
* ⚡ **后端工程**：Python、FastAPI、AsyncIO、SQLAlchemy
* 🎨 **前端开发**：Vue 3、TypeScript、Vite
* 🗄️ **数据存储**：PostgreSQL、MySQL、Redis
* 🔄 **实时交互**：SSE、异步任务、流式输出
* 🐳 **工程化**：Docker、Pytest、Git、Nginx
* 🧩 **浏览器扩展**：WXT、Chrome Extension Manifest V3

目前正在持续深入：

```text
AI Application Engineering
│
├── Agent Architecture
│   ├── Tool Calling
│   ├── Agent Workflow
│   ├── Multi-Agent
│   └── Context Management
│
├── RAG
│   ├── Retrieval
│   ├── Rerank
│   ├── Chunk Strategy
│   └── Evaluation
│
├── Backend Engineering
│   ├── Async Python
│   ├── PostgreSQL
│   ├── Redis
│   ├── Concurrency
│   └── System Design
│
└── AI Engineering
    ├── SSE Streaming
    ├── Structured Output
    ├── Observability
    └── Production Deployment
```

---

# 🚀 精选项目

## 🍽️ YY Kitchen — AI 家庭协同点餐平台

> 面向家庭场景开发的 AI 协同点餐平台，覆盖菜单管理、多人点餐、订单协作、AI 推荐与多模态食材识别。

### 核心能力

* 🤖 基于 **多模态大模型 + RAG** 构建 AI 厨房助手
* 📷 支持上传冰箱图片识别食材，并结合家庭菜品和饮食偏好生成个性化推荐
* 🔎 检索家庭菜品、饮食偏好、历史用餐数据作为推荐上下文
* ⚡ 设计 `ready / delta / complete / error` SSE 事件协议
* 🔐 实现 JWT 鉴权与家庭级数据权限隔离
* 🗄️ 使用 SQLAlchemy Async + PostgreSQL 构建异步数据访问层
* 🏗️ 采用 `API → Service → Repository` 分层架构
* 🔄 使用 Alembic 管理数据库版本
* 🧪 使用 Pytest 覆盖核心业务流程
* 🐳 基于 Docker Compose 完成容器化部署

### 技术栈

`Python` `FastAPI` `Vue 3` `TypeScript` `PostgreSQL`

`SQLAlchemy Async` `Alembic` `JWT` `RAG` `SSE`

`Pytest` `Docker` `Nginx / Caddy`

👉 [查看项目](https://github.com/fengfeng-666/yy--)

---

## 🍳 厨灵 — 多模态 AI 智能菜谱系统

> 基于多模态大模型开发的 AI 菜谱助手，可以通过自然语言或食材图片生成个性化菜谱。

### 核心能力

* 🧠 接入 **Qwen3.5-Omni-Plus** 多模态大模型
* 📷 支持上传食材图片进行识别与菜谱生成
* 💬 实现多轮 AI 对话和聊天历史持久化
* ⚡ 基于 SSE 实现大模型内容实时流式输出
* 🔐 实现用户注册、登录与 JWT 身份认证
* 🗄️ 支持 PostgreSQL 数据持久化
* 🐳 支持 Docker / Docker Compose 部署
* ❤️ 支持菜谱收藏、步骤管理等完整产品功能

### 技术栈

`Python` `FastAPI` `Vue 3` `Qwen`

`PostgreSQL` `SQLAlchemy` `JWT`

`SSE` `Docker`

👉 [查看项目](https://github.com/fengfeng-666/chuling-ai-chef)

---

## 🛒 AI 智能电商平台

> 将传统电商业务与 AI 推荐、RAG 智能问答相结合的全栈应用。

### 核心能力

* 🛍️ 实现商品、分类、购物车、订单等完整电商业务
* 🤖 集成 RAG，实现基于商品数据的智能问答
* 🎯 实现个性化商品推荐能力
* 🔐 基于 JWT / OAuth2 实现用户认证
* 🗄️ 使用 SQLAlchemy 完成 ORM 数据建模
* 🌐 Vue 3 + FastAPI 前后端分离架构
* ✅ 使用 Pydantic 完成请求与响应数据校验

### 技术栈

`Python` `FastAPI` `Vue 3`

`SQLAlchemy` `MySQL`

`RAG` `JWT` `OAuth2`

👉 [查看项目](https://github.com/fengfeng-666/ai-shop-platform)

---

## 🤖 Multi-Agent 软件开发协作实验

> 基于 AutoGen 探索多个 Agent 在软件开发任务中的角色协作和任务编排。

当前主要用于学习与实验：

* Product Manager Agent
* Engineer Agent
* Code Reviewer Agent
* User Proxy Agent
* RoundRobinGroupChat
* Agent System Prompt
* Termination Condition
* Multi-Agent Workflow

### 技术栈

`Python` `AutoGen` `AsyncIO` `LLM`

👉 [查看项目](https://github.com/fengfeng-666/ai-software-team)

> 📌 该项目目前属于 Agent 学习与二次实践项目，正在进一步进行工程化改造。

---

# 💼 工程实践

除了个人项目，我也在真实业务项目中持续进行全栈工程实践。

目前接触和实践的业务方向包括：

* AI 商品推荐
* 新闻热点商品化分析
* 跨境电商商品采集
* Chrome Extension 自动化
* 异步任务处理
* 数据去重与失败重试
* 长任务断点恢复
* JWT / RBAC 权限控制
* PostgreSQL 数据建模
* Docker 服务部署

相比只完成一个 Demo，我更关注：

> **系统能不能稳定运行、异常后能不能恢复、数据是否一致、任务能不能追踪，以及模型能力如何真正接入业务。**

---

# 🧰 技术栈

## 🤖 AI / LLM

<p>
<img src="https://img.shields.io/badge/LLM-Application-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-Retrieval-blueviolet?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI-Agent-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AutoGen-Multi--Agent-blue?style=for-the-badge"/>
</p>

主要实践：

`LLM Integration`

`RAG`

`Agent Workflow`

`Multi-Agent`

`Prompt Engineering`

`Context Management`

`Multimodal`

`Structured Output`

`SSE Streaming`

---

## ⚡ Backend

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
</p>

主要实践：

`FastAPI`

`AsyncIO`

`SQLAlchemy Async`

`RESTful API`

`JWT`

`OAuth2`

`RBAC`

`Middleware`

`Background Tasks`

`SSE`

---

## 🎨 Frontend

<p>
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
</p>

主要实践：

`Vue 3`

`Composition API`

`TypeScript`

`Vite`

`REST API Integration`

`SSE Client`

---

## 🗄️ Database

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

主要关注：

`Index`

`Transaction`

`Concurrency Control`

`Query Optimization`

`Pagination`

`JOIN`

`N+1`

---

## 🐳 DevOps & Engineering

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

主要实践：

`Docker`

`Docker Compose`

`Pytest`

`Git Flow`

`Nginx`

`Health Check`

`Retry`

`Task Recovery`

---

## 🧩 Browser Extension

主要实践：

`Chrome Extension`

`Manifest V3`

`WXT`

`Content Script`

`Service Worker`

`Cross-tab Communication`

`Page Automation`

`Task Queue`

---

# 🧠 当前重点

目前正在重点提升三个方向：

### ① 后端工程能力

```text
Database
   ↓
Concurrency
   ↓
Cache
   ↓
Message Queue
   ↓
Distributed System
   ↓
System Design
```

### ② AI 应用工程

```text
Prompt
   ↓
RAG
   ↓
Tool Calling
   ↓
Agent
   ↓
Evaluation
   ↓
Production
```

### ③ AI 全栈产品能力

```text
需求
 ↓
前端
 ↓
API
 ↓
数据库
 ↓
LLM / Agent
 ↓
测试
 ↓
Docker
 ↓
部署
```

目标不是单纯“调用一个模型”。

而是：

> **能够独立完成一个 AI 产品从需求、架构、开发到部署的完整闭环。**

---

# 📊 GitHub 数据

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=fengfeng-666&show_icons=true&hide_border=true&include_all_commits=true&count_private=true"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fengfeng-666&layout=compact&hide_border=true"/>

</div>

---

# 📌 推荐查看

如果你第一次来到我的 GitHub，可以优先看看：

1. 🍽️ **YY Kitchen**
   AI 全栈 / RAG / 多模态 / SSE / PostgreSQL / Docker

2. 🍳 **厨灵 AI Chef**
   多模态 LLM / FastAPI / Vue3 / 流式 AI 应用

3. 🛒 **AI Shop Platform**
   RAG / 电商业务 / FastAPI / Vue3

---

<div align="center">

## 💡 Build → Understand → Improve

### 不只让代码跑起来，也想弄清楚它为什么这样运行。

<br/>

**AI Application · Backend Engineering · Full Stack**

</div>
