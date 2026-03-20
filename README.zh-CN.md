# Awesome Academic Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Projects](https://img.shields.io/badge/projects-21-blue.svg)](#categories) [![Categories](https://img.shields.io/badge/categories-7-0a7b83.svg)](#categories) [![License: MIT](https://img.shields.io/badge/license-MIT-lightgrey.svg)](LICENSE)

[English](README.md) | [简体中文](README.zh-CN.md)

> 一个聚焦学术场景的开源 AI 工具、研究代理、MCP 服务器与可复用技能清单，覆盖文献检索、论文阅读、信息综合与学术写作。

这个仓库面向研究者、学生，以及正在搭建学术 AI 工作流的开发者，帮助你快速理解正在形成中的 academic AI workflow stack。

它关注的是那些真正能支持研究工作落地的工具，而不只是泛 AI 包装层：

- 发现并收集论文
- 阅读、总结并综合文献内容
- 将学术资料库接入 AI 助手
- 复用研究技能与写作工作流
- 探索更自动化的 agent 式学术流程

## 一览

- 收录 7 个类别、21 个精选项目
- 重点关注开源学术工作流，而不是通用 AI 包装工具
- 面向实际使用场景组织，而不只是做生态观察

## 为什么要做这个列表

围绕学术软件、PDF 阅读器和通用 AI 工具的清单已经很多，但它们通常会落入两类：

- 停留在传统研究工具范畴
- 把学术场景混在更宽泛的 AI 目录里

这个项目处在两者之间。它追踪的是那些能让 agent 辅助学术工作真正进入可用工作流的工具、技能和集成方式。

## 适合谁使用

- 正在做文献综述、论文阅读、毕业论文的学生
- 想探索 AI 辅助综合分析与起草写作的研究者
- 正在为实验室或团队搭建内部研究助手与工作流的开发者
- 希望打通 MCP server、论文资料库与复用技能的高级用户

## 如何使用这个列表

从你当前最关心的研究阶段开始：

1. 用论文发现工具和 paper-search MCP server 找到相关文献。
2. 用面向论文的技能和 deep research 工作流加快阅读。
3. 通过 Zotero 或其他 agent 集成连接你的文献库。
4. 借助写作工作流，把笔记推进成提纲、综述和初稿。
5. 当你需要端到端自动化时，再探索更自主的研究 agent 流程。

## 分类

| 分类 | 数量 | 覆盖内容 |
| --- | ---: | --- |
| [文献综述与论文发现](categories/literature-review-and-paper-discovery.md) | 2 | 论文搜索、检索与发现工作流 |
| [阅读、总结与深度研究](categories/reading-summarization-and-deep-research.md) | 8 | 阅读助手、信息抽取与多阶段综述 |
| [自主研究代理](categories/autonomous-research-agents.md) | 6 | 可进行构思、规划、执行和汇报的研究 agent |
| [学术写作与研究工作流](categories/academic-writing-and-research-workflows.md) | 4 | 提纲、草稿与结构化写作流程 |
| [研究技能与提示词库](categories/research-skills-and-prompt-libraries.md) | 4 | 面向重复研究任务的可复用技能 |
| [MCP 服务器与 Agent 集成](categories/mcp-servers-and-agent-integrations.md) | 5 | 面向论文搜索、Zotero 与学术工具的连接器 |
| [Awesome 清单与生态地图](categories/awesome-lists-and-ecosystem-maps.md) | 2 | 更宏观的 academic AI 生态索引 |

## 推荐起步路径

### 文献综述起步

- [openags/paper-search-mcp](https://github.com/openags/paper-search-mcp)
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server)
- [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)

如果你想快速从研究主题走到一组可用论文，可以先走这条路径。

### 阅读与综合分析栈

- [opendatalab/MinerU](https://github.com/opendatalab/MinerU)
- [Future-House/paper-qa](https://github.com/Future-House/paper-qa)
- [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp)

如果你已经有论文，接下来更需要解析能力、基于证据的回答和与文献库联动的综合分析，这条路径更合适。

### 写作导向工作流

- [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer)
- [Future-House/paper-qa](https://github.com/Future-House/paper-qa)
- [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)

如果你的主要目标是把参考文献和基于证据的笔记推进成草稿，这条路径更合适。

### 进阶 Agent 工作流

- [HKUDS/AI-Researcher](https://github.com/HKUDS/AI-Researcher)
- [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2)
- [stanford-oval/storm](https://github.com/stanford-oval/storm)

如果你想尝试更自主的文献综述、研究构思和端到端研究 agent 实验，可以从这里开始。

## 收录原则

这里的项目通常应满足：

- 开源
- 与真实学术工作流相关
- 能支持文献发现、阅读、综合、写作或学术系统集成
- 通过 agent、MCP、可复用技能或工作流自动化带来明显增益

以下项目通常不会收录：

- 纯闭源 SaaS 产品
- 没有学术聚焦的通用 AI 包装工具
- 与 AI 工作流无关的传统学术工具
- 信息量很低的演示项目或已废弃仓库

## 安全说明

这是一个精选清单，不是安全审计报告。

研究技能、MCP server 和 agent 工作流可能拥有较广泛的文件、浏览器、API 或资料库访问权限。在真实的学术环境或机构环境中使用前，请先审阅源码和权限边界。

## 贡献

欢迎提交贡献。收录范围、条目格式与提交流程见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 许可

[MIT](LICENSE)
