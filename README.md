<div align="center">

# Hzwuu

**软件工程学生 · AI 应用开发 · Python 后端**

我在意的不只是模型能不能回答，更是系统有没有依据、会不会失败、能不能复现。

`Python` · `C/C++` · `RAG` · `FastAPI` · `SQLite` · `Streamlit`

**目前正在寻找 AI 应用开发或 Python 后端方向实习机会。**

</div>

---

## 关于我

目前主要做本地 RAG、Agent 应用和后端工程实践。项目优先保证可控的知识来源、明确的安全边界、可解释的失败回退，以及可以重复运行的测试。

## 当前关注

- 本地知识检索、来源追溯与上下文约束
- FastAPI、SQLite 和接口设计
- pytest、GitHub Actions 和可复现工程流程
- 正在学习 SQLAlchemy、Vue3 和 Docker

## 代表项目

### [TCM Consultation RAG](https://github.com/Hzwuu/tcm-consultation-rag)

中医问诊辅助本地 RAG 原型。从结构化 CSV 检索 Top 3 知识记录，并把候选、依据和来源注入生成上下文；包含红旗症状分流、低置信度停止、大模型失败回退和 CI。

`Python` `C++` `RAG` `TF-IDF` `Embedding` `Streamlit` `GitHub Actions`

### [Debate Agent](https://github.com/Hzwuu/debate-agent)

持久化多智能体辩论后端。使用 FastAPI、SQLite 和分阶段执行保存辩论过程，支持证据检索、引用审计、模型调用记录与离线 Mock 模式。

`Python` `FastAPI` `SQLite` `Multi-Agent` `pytest`

### [AI Video Analyzer](https://github.com/Hzwuu/AI-Video-Analyzer)

短视频数据评分与生产辅助项目。按周迭代数据存储、后端接口、自动测试和 CI，目前继续扩展 FastAPI 服务。

`Python` `FastAPI` `SQLite` `pytest` `ruff`

### [Deep Research](https://github.com/Hzwuu/deep-research)

基于 LangGraph 的研究 Agent 实验，探索多轮对话、工具调用、信息检索和研究结果组织。

`Python` `LangGraph` `RAG` `Tool Calling`

### [DSA Practicum](https://github.com/Hzwuu/dsa-practicum)

六个 C 语言数据结构与算法课题，覆盖线性表、栈、队列、二叉树、图、Huffman、DFS/BFS、Dijkstra 和 Prim。

`C` `Data Structures` `Algorithms`

## 工程原则

- 先保证能够运行和复现，再讨论模型效果。
- 来源、回退逻辑和已知限制与功能一起说明。
- 核心项目尽量具备 README、测试、CI 和清晰的提交记录。
- 不把检索候选、模型输出和医疗结论混为一谈。

---

<div align="center">

如果项目对你有帮助，欢迎查看代码、提交 Issue 或交流实现思路。

</div>
