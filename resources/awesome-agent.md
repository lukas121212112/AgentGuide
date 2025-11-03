# Awesome Agent - AI Agent 开发核心资源

> **精选** AI Agent 开发的**核心资源**（只推荐最重要的！）

**📌 定位说明**：
- ✅ 只收录 Agent 开发**直接相关**的资源
- ✅ 只推荐**面试会考**、**项目会用**的
- ✅ 每个资源都标注**适合场景**和**学习难度**

**🔗 需要更全面的资源？**  
查看作者的另一个项目：[Awesome-Awesome-LLM](https://github.com/adongwanai/Awesome-Awesome-LLM)  
（涵盖 LLM 全栈的 200+ Awesome 系列资源）

---

**⭐ 本文档持续更新，欢迎贡献！**

---

## 🏗️ Agent 开发框架

> **详细框架对比见**：[Agent 开发框架推荐](./frameworks.md)

### 1. LangGraph ⭐⭐⭐⭐⭐ 最推荐
- **链接**：https://github.com/langchain-ai/langgraph
- **Stars**：15k+
- **简介**：LangChain 团队出品，用图结构构建弹性 Agent
- **特点**：状态管理、可视化工作流、灵活编排
- **适合场景**：复杂 Agent 工作流、Multi-Agent 系统
- **学习难度**：⭐⭐⭐⭐
- **AgentGuide 教程**：[LangGraph 核心概念](../docs/02-tech-stack/04-langchain-guide.md)

### 2. AutoGen ⭐⭐⭐⭐⭐
- **链接**：https://github.com/microsoft/autogen
- **Stars**：30k+
- **简介**：微软开源的多智能体对话框架
- **特点**：Multi-Agent 协作、可视化 Studio、代码执行
- **适合场景**：多智能体系统、角色扮演型 Agent
- **学习难度**：⭐⭐⭐
- **官网**：https://autogen-studio.com/

### 3. CrewAI ⭐⭐⭐⭐
- **链接**：https://github.com/joaomdmoura/crewAI
- **Stars**：20k+
- **简介**：角色扮演型自主 AI Agent 框架
- **特点**：角色定义、任务分工、简单易用
- **适合场景**：明确角色分工的协作系统

### 4. MetaGPT ⭐⭐⭐⭐
- **链接**：https://github.com/geekan/MetaGPT
- **Stars**：40k+
- **简介**：软件公司多角色协作框架
- **特点**：模拟软件公司流程（PM、工程师、测试）

### 5. Swarm ⭐⭐⭐
- **链接**：https://github.com/openai/swarm
- **简介**：OpenAI 官方的轻量级 Multi-Agent 框架
- **特点**：极简设计，适合学习

### 6. AutoGPT ⭐⭐⭐
- **链接**：https://github.com/Significant-Gravitas/AutoGPT
- **Stars**：160k+
- **简介**：早期的自主 Agent 框架
- **特点**：完全自主，目标驱动

### 7. Microsoft Agent Framework ⭐⭐⭐
- **链接**：https://github.com/microsoft/agent-framework
- **简介**：微软官方框架，支持 Python 和 .NET
- **特点**：企业级、跨语言

### 8. OWL ⭐⭐⭐
- **链接**：https://github.com/camel-ai/owl
- **简介**：优化工作流学习框架
- **特点**：任务自动化、工作流优化

---

## 🔧 工具调用 (Tool Use)

### 1. ToolBench ⭐⭐⭐⭐
- **链接**：https://github.com/OpenBMB/ToolBench
- **简介**：工具学习基准测试
- **包含**：16000+ 真实 API、工具调用数据集

### 2. Gorilla ⭐⭐⭐⭐
- **链接**：https://github.com/ShishirPatil/gorilla
- **简介**：大模型 API 调用优化
- **特点**：专注于提升工具调用准确性

### 3. ToolLLM ⭐⭐⭐⭐
- **链接**：https://github.com/OpenBMB/ToolLLM
- **简介**：工具学习的 LLM 训练

---

## 💾 记忆模块 (Memory)

### 1. Mem0 ⭐⭐⭐⭐⭐
- **链接**：https://github.com/mem0ai/mem0
- **Stars**：20k+
- **简介**：轻量级 Agent 记忆模块
- **特点**：简单易用、支持多种后端
- **注意**：社区反馈有稳定性问题，使用前需验证

### 2. MemGPT ⭐⭐⭐⭐
- **链接**：https://github.com/cpacker/MemGPT
- **简介**：长期记忆管理系统
- **特点**：虚拟内存机制

### 3. Zep ⭐⭐⭐⭐
- **链接**：https://github.com/getzep/zep
- **简介**：长期记忆存储
- **特点**：企业级、可扩展

### 4. LangChain Memory
- **文档**：https://python.langchain.com/docs/modules/memory/
- **简介**：LangChain 内置记忆模块
- **特点**：多种记忆类型

---

## 🕷️ GUI Agent / Web Agent

### 1. AppAgent ⭐⭐⭐⭐
- **链接**：https://github.com/mnotgod96/AppAgent
- **简介**：移动应用 Agent
- **特点**：自主操作手机应用

### 2. SeeAct ⭐⭐⭐⭐
- **链接**：https://github.com/OSU-NLP-Group/SeeAct
- **简介**：视觉理解 + 网页操作
- **特点**：GPT-4V 驱动

### 3. WebShop ⭐⭐⭐⭐
- **链接**：https://github.com/princeton-nlp/WebShop
- **简介**：在线购物 Agent 基准测试

### 4. Mind2Web ⭐⭐⭐⭐
- **链接**：https://github.com/OSU-NLP-Group/Mind2Web
- **简介**：网页任务理解数据集

### 5. WebArena ⭐⭐⭐⭐
- **简介**：Web Agent 评估基准

---

## 📊 评估 Benchmark

### Agent 评估
1. **GAIA** - 通用 AI Agent 评估
2. **AgentBench** - Agent 综合能力评估
3. **WebArena** - Web Agent 评估
4. **ToolBench** - 工具使用评估

---

## 📚 必读论文

### 核心论文
1. **ReAct** ⭐⭐⭐⭐⭐
   - 论文：https://arxiv.org/abs/2210.03629
   - 必读原因：Agent 架构基础

2. **Reflexion** ⭐⭐⭐⭐⭐
   - 论文：https://arxiv.org/abs/2303.11366
   - 必读原因：自我反思机制

（更多论文待填充...）

---

## 🎓 学习资源

### 官方指南
1. **Anthropic - Building Effective Agents** ⭐⭐⭐⭐⭐
   - 链接：https://www.anthropic.com/engineering/building-effective-agents
   - 核心观点：何时该用 Agent，何时不该用

2. **OpenAI - A Practical Guide to Building Agents**
   - 链接：https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf

3. **Agentic Design Patterns（中文版）**
   - 链接：https://github.com/ginobefun/agentic-design-patterns-cn

### 开源教程
- RAG from Scratch：https://github.com/langchain-ai/rag-from-scratch
- LangChain 中文教程：https://github.com/liaokongVFX/LangChain-Chinese-Getting-Started-Guide

---

## 🔗 相关文档

- [RAG 资源大全](./awesome-rag.md)
- [训练资源大全](./awesome-training.md)
- [多模态资源大全](./awesome-multimodal.md)
- [AI 开发工具箱](./tools.md)

---

**🙏 欢迎贡献**：如果你发现好的 Agent 相关资源，欢迎提 PR！

