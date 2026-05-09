# Jhao-Agent-AutoFront

基于 **LangGraph 编排 Agent 工作流**，实现 AI 驱动的前端网页自动化生成。

## 🚀 功能

- 自然语言描述需求，自动生成前端页面代码
- LangGraph 多 Agent 协作：需求分析 → 组件生成 → 代码组装
- 集成 Sandpack 在线预览生成的代码
- 支持将生成的项目导出为 ZIP 下载

## 🛠 技术栈

### 前端
- **Next.js 16** + React 19 + TypeScript
- **Tailwind CSS 4** + Ant Design X
- **Zustand** 状态管理
- **Sandpack** 在线代码预览
- **Lucide React** 图标库

### 后端
- **Express** + TypeScript
- **LangChain** + **LangGraph** Agent 编排
- **OpenAI** 大模型驱动
- **MCP SDK** 工具调用
- **Zod** 数据校验
- **Ali OSS** 文件存储

## 📁 项目结构
├── frontend/ # Next.js 前端
├── server/ # Express + LangGraph 后端
└── README.md


## ⚡ 快速开始

```bash
# 前端
cd frontend
npm install
npm run dev

# 后端
cd server
npm install
npm run dev
