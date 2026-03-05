# rag-agent-knowledge-assistant
🤖 RAG-Agent Knowledge Assistant

基于 RAG + Agent 架构的智能知识问答系统
一个结合 向量检索、Agent推理与工具调用 的智能知识库问答系统。
系统能够对本地知识库进行语义检索，并通过大模型推理生成高质量回答。

📖 项目介绍

本项目实现了一个完整的 RAG（Retrieval Augmented Generation）+ Agent 架构的 AI 问答系统。
系统将本地知识文档进行向量化存储，通过 Chroma 向量数据库进行语义检索，再结合 Agent 推理机制与大模型生成最终回答。

🧩 核心功能
1️⃣ RAG 知识检索

文档向量化
相似度搜索
知识增强生成回答
支持本地知识库问答
使用 ChromaDB 实现向量存储与语义搜索。

⭐ 项目亮点


实现完整 RAG 检索增强生成流程
构建 Agent 推理 + 工具调用架构
使用 ChromaDB 实现语义向量检索
支持 多文档知识库问答
采用 Prompt 模板优化回答质量
具备 可扩展工具系统