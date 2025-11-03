# Awesome RAG - RAG 核心资源精选

> **精选** RAG（检索增强生成）的**核心资源**（只推荐最实用的！）

**📌 定位说明**：
- ✅ 只收录 RAG 开发**直接会用**的资源
- ✅ 只推荐**生产环境验证过**的工具
- ✅ 每个资源都标注**适合场景**和**学习成本**

**🔗 需要更全面的 LLM 资源？**  
查看：[Awesome-Awesome-LLM](https://github.com/adongwanai/Awesome-Awesome-LLM)  
（涵盖训练、推理、部署等 LLM 全栈资源）

---

**⭐ 本文档持续更新，欢迎贡献！**

---

## 🔥 RAG 开发框架

### 1. LangChain ⭐⭐⭐⭐⭐
- **链接**：https://github.com/langchain-ai/langchain
- **Stars**：90k+
- **简介**：最流行的 LLM 应用开发框架
- **特点**：生态完善、文档详细、组件丰富
- **适合场景**：快速原型开发、RAG 系统构建
- **AgentGuide 教程**：[LangChain 核心概念](../docs/02-tech-stack/04-langchain-guide.md)

### 2. LlamaIndex ⭐⭐⭐⭐⭐
- **链接**：https://github.com/run-llama/llama_index
- **Stars**：35k+
- **简介**：专注于数据索引和 RAG 的框架
- **特点**：数据连接器丰富、索引能力强
- **适合场景**：企业知识库、文档问答
- **AgentGuide 教程**：[LlamaIndex 核心概念](../docs/02-tech-stack/05-llamaindex-guide.md)

### 3. Haystack ⭐⭐⭐⭐
- **链接**：https://github.com/deepset-ai/haystack
- **Stars**：15k+
- **简介**：端到端 NLP 框架，强大的 RAG 能力

### 4. RAGFlow ⭐⭐⭐⭐
- **链接**：https://github.com/infiniflow/ragflow
- **简介**：开箱即用的 RAG 引擎
- **特点**：可视化、低代码

### 5. Dify ⭐⭐⭐⭐
- **链接**：https://github.com/langgenius/dify
- **Stars**：40k+
- **简介**：LLM 应用开发平台
- **特点**：可视化、工作流编排

---

## 📊 向量数据库

### 生产级向量库

#### 1. Milvus ⭐⭐⭐⭐⭐ 最推荐
- **链接**：https://github.com/milvus-io/milvus
- **Stars**：28k+
- **简介**：开源分布式向量数据库
- **特点**：高性能、可扩展、支持多种索引
- **适合场景**：生产环境、大规模数据
- **AgentGuide 教程**：[向量数据库实战](../docs/02-tech-stack/09-vector-db-comparison.md)

#### 2. Weaviate ⭐⭐⭐⭐
- **链接**：https://github.com/weaviate/weaviate
- **Stars**：10k+
- **简介**：向量搜索引擎
- **特点**：支持混合检索、GraphQL API

#### 3. Qdrant ⭐⭐⭐⭐
- **链接**：https://github.com/qdrant/qdrant
- **Stars**：19k+
- **简介**：高性能向量数据库
- **特点**：Rust 编写，性能优秀

#### 4. Pinecone ⭐⭐⭐⭐
- **链接**：https://www.pinecone.io/
- **简介**：托管式向量数据库（收费）
- **特点**：完全托管、易于使用

### 轻量级向量库

#### 5. Chroma ⭐⭐⭐⭐
- **链接**：https://github.com/chroma-core/chroma
- **Stars**：14k+
- **简介**：轻量级向量数据库
- **适合场景**：本地开发、小规模应用

#### 6. FAISS ⭐⭐⭐⭐⭐
- **链接**：https://github.com/facebookresearch/faiss
- **Stars**：30k+
- **简介**：Facebook 开源的向量检索库
- **特点**：极致性能、多种索引算法
- **适合场景**：本地检索、高性能要求

---

## 🔤 Embedding 模型

### 1. BGE (BAAI General Embedding) ⭐⭐⭐⭐⭐
- **链接**：https://github.com/FlagOpen/FlagEmbedding
- **简介**：智源开源的 Embedding 模型
- **特点**：中文友好、性能优秀
- **模型系列**：BGE-small、BGE-base、BGE-large

### 2. E5 ⭐⭐⭐⭐
- **链接**：https://github.com/microsoft/unilm/tree/master/e5
- **简介**：微软的 Embedding 模型
- **特点**：多语言支持

### 3. Sentence-Transformers ⭐⭐⭐⭐⭐
- **链接**：https://github.com/UKPLab/sentence-transformers
- **Stars**：14k+
- **简介**：句子级 Embedding 框架
- **特点**：易用、模型丰富

### 4. Instructor ⭐⭐⭐⭐
- **链接**：https://github.com/xlang-ai/instructor-embedding
- **简介**：指令式 Embedding 模型
- **特点**：任务自适应

---

## 📄 文档解析

### 1. MinerU ⭐⭐⭐⭐⭐ 最推荐
- **链接**：https://github.com/opendatalab/MinerU
- **Stars**：10k+
- **简介**：强大的 PDF 解析工具
- **特点**：支持复杂 PDF、表格、图片
- **适合场景**：企业文档解析、多模态 RAG

### 2. Unstructured ⭐⭐⭐⭐
- **链接**：https://github.com/Unstructured-IO/unstructured
- **简介**：多格式文档解析
- **特点**：支持 20+ 种文档格式

### 3. LlamaParse ⭐⭐⭐⭐
- **链接**：https://github.com/run-llama/llama_parse
- **简介**：LlamaIndex 官方解析工具
- **特点**：与 LlamaIndex 深度集成

### 4. Docling ⭐⭐⭐
- **链接**：https://github.com/DS4SD/docling
- **简介**：IBM 开源的文档解析工具

### 5. PyPDF2
- **链接**：https://github.com/py-pdf/pypdf2
- **简介**：Python PDF 处理库
- **特点**：基础功能、轻量级

---

## 🎯 高级 RAG 技术

### GraphRAG
- **链接**：微软技术报告
- **简介**：基于知识图谱的 RAG
- **特点**：多跳推理、关系理解

### HyDE (Hypothetical Document Embeddings)
- **论文**：https://arxiv.org/abs/2212.10496
- **简介**：假设文档 Embedding
- **特点**：查询改写

### Query Rewriting
- 多查询生成
- Query 扩展
- Query 分解

---

## 📚 必读论文

### 检索算法
1. **Dense Passage Retrieval** ⭐⭐⭐⭐⭐
   - 论文：https://arxiv.org/abs/2004.04906
   - 核心：密集检索 vs 稀疏检索

2. **ColBERT**
   - 论文：https://arxiv.org/abs/2004.12832
   - 核心：后期交互检索

### RAG 优化
3. **Self-RAG**
   - 论文：https://arxiv.org/abs/2310.11511
   - 核心：自我反思的 RAG

4. **CRAG (Corrective RAG)**
   - 核心：纠错式 RAG

### 评估
5. **RAGAS**
   - 论文：https://arxiv.org/abs/2309.15217
   - 核心：RAG 评估框架

---

## 🔗 数据集

### RAG 评估数据集
- **HotpotQA**：多跳推理问答
- **Natural Questions**：Google 问答数据集
- **MS MARCO**：微软问答数据集
- **KGQA**：知识图谱问答

---

## 🛠️ 实用工具

### Reranker 模型
- **BGE-Reranker**：智源 Reranker
- **Cohere Rerank**：Cohere 官方

### 检索优化
- **BM25**：经典稀疏检索
- **Hybrid Search**：混合检索

---

## 🎓 学习资源

### 教程
- **RAG from Scratch**：https://github.com/langchain-ai/rag-from-scratch
- **LlamaIndex 官方教程**：https://docs.llamaindex.ai/

### 博客
- Pinecone Blog
- LlamaIndex Blog
- LangChain Blog

---

## 📝 相关 AgentGuide 章节

- [向量数据库基础](../docs/02-tech-stack/08-vector-db-basics.md)
- [RAG 检索策略详解](../docs/02-tech-stack/10-rag-strategies.md)
- [LlamaIndex 核心概念](../docs/02-tech-stack/05-llamaindex-guide.md)

---

**👉 返回主文档**：[README.md](../README.md)  
**👉 查看 Agent 资源**：[Awesome Agent](./awesome-agent.md)

---

**📌 说明**：
- ⭐ 数量代表推荐程度
- 本文档会持续更新
- 欢迎提交 PR 补充资源

