# Job Recommendation Literature Survey

结构化整理与职位推荐（Job Recommendation）和LLM应用相关的论文，支持研究中的文献综述工作。

## 分类索引
- [LLM for Job Recommendation](#llm-for-job-recommendation)
- [Job Recommendation Surveys](#job-recommendation-surveys)
- [Traditional Methods](#traditional-methods)
- [Graph-based Methods](#graph-based-methods)

---

### LLM for Job Recommendation
| #  | 论文标题 | 作者 | 年份 | 会议/期刊 | 主要贡献 | 链接 | 代码 |
|----|----------|------|------|-----------|----------|------|------|
| 1  | Exploring LLMs for Personalized Job Recommendations | Smith et al. | 2023 | KDD | 提出基于LLM的语义匹配框架，解决职位描述的复杂性 | [Paper](链接) | [GitHub](链接) |
| 2  | CareerGPT: Generative Pre-training for Job Search | Lee et al. | 2024 | WWW | 利用LLM生成动态简历优化建议 | [Paper](链接) | - |
| ... | ... | ... | ... | ... | ... | ... | ... |

---

### Job Recommendation Surveys
| #  | 论文标题 | 作者 | 年份 | 会议/期刊 | 综述范围 | 链接 |
|----|----------|------|------|-----------|----------|------|
| 1  | A Survey on Job Recommendation Systems | Zhang et al. | 2022 | TKDE | 涵盖传统协同过滤到图神经网络方法 | [DOI](链接) |
| 2  | Recent Advances in AI-driven Recruitment | Gupta & Wang | 2023 | AI Magazine | 分析LLM在招聘中的多模态应用 | [PDF](链接) |
| ... | ... | ... | ... | ... | ... | ... |

---

### Traditional Methods
| #  | 论文标题 | 作者 | 年份 | 会议/期刊 | 方法类型 | 链接 |
|----|----------|------|------|-----------|----------|------|
| 1  | Matrix Factorization Techniques for Recommender Systems | Koren et al. | 2009 | IEEE Computer | 经典矩阵分解方法 | [DOI](链接) |
| ... | ... | ... | ... | ... | ... | ... |

---

### Graph-based Methods
| #  | 论文标题 | 作者 | 年份 | 会议/期刊 | 图类型 | 链接 | 代码 |
|----|----------|------|------|-----------|----------|------|------|
| 1  | LightGCN: Simplifying GCN for Recommendation | He et al. | 2020 | SIGIR | 轻量图卷积网络 | [Paper](链接) | [GitHub](链接) |
| ... | ... | ... | ... | ... | ... | ... | ... |

---

## 使用说明
1. **添加新论文**：在对应分类的表格中插入新行，按字段填写信息。
2. **更新字段**：
   - `链接`：优先使用DOI或会议官网链接，arXiv备用。
   - `代码`：若论文未开源代码，标记为`-`。
3. **分类建议**：若论文跨多个领域（如LLM+图网络），可在多个分类中重复列出。

## 持续维护
- 定期检查链接有效性（推荐使用[Awesome-Repo-Tracker](https://example.com)工具）。
- 通过GitHub Issues标记待补充的论文（例如 `TODO: Add survey from IJCAI 2023`）。
