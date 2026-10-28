<div align="center">
  <img src="./public/logo.png" alt="BibGenie logo" width="112"/>

  # BibGenie

  ### Zotero 内的 AI 研究智能体

  [English](README.MD) | [简体中文](README_ZH.MD)

  [![Zotero 7, 8, 9 and 10](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-cc2936)](https://www.zotero.org/)
  [![官网](https://img.shields.io/badge/Website-bibgenie.com-2563eb)](https://www.bibgenie.com/zh)
  [![文档](https://img.shields.io/badge/Docs-开始使用-0f766e)](https://www.bibgenie.com/zh/docs)
  [![Discord](https://img.shields.io/badge/Discord-Community-5865f2)](https://discord.gg/kDXFAAYDNE)
  [![GitHub Downloads](https://img.shields.io/github/downloads/BaiRuic/BibGenie/total?logo=github)](https://github.com/BaiRuic/BibGenie/releases)
  [![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/BaiRuic/BibGenie)

  > **让 AI 处理材料，把理解留给研究者。**

  **BibGenie 原生运行在 Zotero 内部，围绕你的论文、笔记、网页快照、批注高亮与文库结构工作。添加研究上下文，提出有依据的问题，追溯证据至原文段落，检索并安全整理文献库，再把有价值的洞察保存回 Zotero 与 Notion。**

  [免费下载插件](https://www.bibgenie.com/zh/download) · [查看文档](https://www.bibgenie.com/zh/docs) · [关于 BibGenie](https://www.bibgenie.com/zh/about) · [加入 Discord](https://discord.gg/kDXFAAYDNE)
</div>

---

## 为什么需要 BibGenie？

随着大语言模型的进步，总结上百篇论文变得前所未有地轻松。然而，一份漂亮的摘要并不代表深度思考已经真正发生。总结中的每句话或许都流畅自洽，但严谨的学术判断始终需要追问：*这个结论究竟出自哪里？原文给出了什么实证证据？在怎样的条件下成立？有哪些未言明的前提或反例？*

BibGenie 常驻在 Zotero 侧边栏中，旨在消除研究中的琐碎摩擦——查找附件、比对方法、搬运整理，同时让学者时刻与第一手证据保持紧密连接。

<p align="center">
  <img src="./public/blocks/demo-workflow.gif" alt="BibGenie 在 Zotero 内添加上下文、围绕论文提问并保存结果的工作流" width="860"/>
  <br/>
  <sub>完整研究工作流预览：添加上下文、阅读论文、保存结果。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/add_context_read_save_lq.mp4">查看高清原视频</a></sub>
</p>

---

## 核心功能

### 1. 引入任意 Zotero 上下文
无需把学术材料反复复制到独立的网页聊天框，直接把你的 Zotero 工作区带入对话：
- 使用 `@` 快捷菜单或右键 **Add to Chat** 添加文献条目、PDF 附件、网页快照、笔记、标签或分类目录。
- 引入划线段落、当前阅读页上下文、论文图表、数学公式选区或粘贴截图。
- 在 Zotero 阅读器中就地向 AI 提问并解析复杂图示与算法推导。

<p align="center">
  <img src="./public/blocks/demo-at-context.gif" alt="在 BibGenie 中使用 @ 菜单添加 Zotero 上下文" width="760"/>
  <br/>
  <sub>使用 <code>@</code> 添加 Zotero 材料。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/at_any_context.mp4">查看高清原视频</a></sub>
</p>

<p align="center">
  <img src="./public/blocks/demo-explain-image.gif" alt="BibGenie 解释 Zotero PDF 中选取的图表" width="760"/>
  <br/>
  <sub>讨论 reader 中的图表与截图。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/explain_image.mp4">查看高清原视频</a></sub>
</p>

### 2. 回答可溯源，一键回跳原文高亮
- BibGenie 的回答在每一个关键断言旁生成段落级引用标记。
- 点击引用标记，**直接跳回 Zotero PDF/EPUB 阅读器中对应段落并自动高亮**。
- 方便就近阅读前后限定条件、核查实验图表与研究方法，从根本上告别 AI 幻觉。

### 3. 文献库检索与本地语义理解
- 支持按标题、作者、年份、DOI、标签、分类、期刊或会议等字段精准筛选。
- 具备**本地语义向量索引**能力，基于文献标题与摘要理解研究意图，无需完全死记关键词即可发现相关论文。
- 向量计算与本地索引完全保存在你的计算机上。

<p align="center">
  <img src="./public/blocks/search_paper_compres.png" alt="BibGenie 检索并阅读 Zotero 文献库中的论文" width="860"/>
</p>

### 4. 跨越文库的学术发现 (OpenAlex 与联网检索)
- **OpenAlex 学术探索**：无缝连接全球数亿条公开学术元数据，检索文库之外的相关研究，梳理引用网络与学科演进脉络。
- **联网搜索与正文提取 (Web Search & Extract)**：实时获取最新公开网页资讯并提取结构化正文，补充前沿与跨学科动态。

### 5. 整理文献库：严格先预览后执行
- 协助清理冗余标签、重构分类层级，并审查批量元数据字段。
- **人工审批确认**：凡涉及文献库写操作（移动文献、加标签、修改元数据），BibGenie 都会先弹出拟议变更卡片，列明受影响条目及前后对比。在你明确点击批准前，绝不擅自修改文库。

<p align="center">
  <img src="./public/blocks/organize_library_compress.png" alt="BibGenie 以先预览后执行的方式整理 Zotero 文献库" width="860"/>
</p>

### 6. 知识沉淀与外部笔记生态联动 (Notion)
- **保存为 Zotero 笔记**：将多篇论文横向比对表格、概念剖析或综述大纲一键保存为关联的 Zotero 子笔记或独立笔记。
- **Notion 笔记联动**：支持通过 Notion MCP 协议连接你授权的 Notion 工作区，在对话中直接查询文献笔记，或将研究结论同步至外部知识库。

### 7. 本地内置 Zotero MCP 服务
- BibGenie 内置本地 **Model Context Protocol (MCP)** 服务端。
- 赋能外部主流开发与研究智能体——如 **Cursor、Claude Desktop、Claude Code、Cherry Studio** 等——让它们直接安全读取你的 Zotero 条目、附件快照并管理笔记。

### 8. 灵活的模型生态与自主隐私保障
- **开箱即用官方额度**：内置精选托管模型，新用户无需配置 Key 即可上手体验。
- **自定义模型与自有 Key (Custom Models)**：直接接入 OpenAI、Anthropic、DeepSeek、Gemini、OpenRouter、Groq 或任何兼容 OpenAI 规范的模型服务，请求直连服务商。
- **本地纯离线推理 (Local Models)**：原生支持 Ollama 和 LM Studio 本地运行，敏感研究资料完全留在本地设备。
- **本地隐私存储**：聊天记录与向量索引默认存储在 Zotero 本地数据库中。

---

## 安装使用

### 系统要求
- **Zotero 7、Zotero 8、Zotero 9 或 Zotero 10**
- Windows、macOS 或 Linux

### 安装步骤
1. 从 [BibGenie 下载页](https://www.bibgenie.com/zh/download) 或 [GitHub Releases](https://github.com/BaiRuic/BibGenie/releases) 下载最新 `.xpi` 插件文件。
2. 在 Zotero 中打开菜单 **Tools -> Plugins**（工具 -> 插件）。
3. 点击右上角齿轮图标，选择 **Install Plugin From File...**。
4. 选择下载好的 `bibgenie-<version>.xpi` 文件，确认安装并重启 Zotero。
5. 从 Zotero 顶部工具栏或 **Tools -> BibGenie** 即可打开侧边面板。

BibGenie 会在 Zotero 启动时自动检查更新；你也可以在 Zotero 插件管理页为其开启自动更新。

---

## 官方文档

- [快速入门指南](https://www.bibgenie.com/zh/docs/getting-started)
- [可溯源引用与原文回跳](https://www.bibgenie.com/zh/docs/bibgenie-citations)
- [添加研究上下文](https://www.bibgenie.com/zh/docs/add-context)
- [文献库语义索引](https://www.bibgenie.com/zh/docs/semantic-index)
- [文献库检索指南](https://www.bibgenie.com/zh/docs/literature-search)
- [OpenAlex 学术探索](https://www.bibgenie.com/zh/docs/openalex-research)
- [自定义模型与 API Key](https://www.bibgenie.com/zh/docs/custom-models)
- [本地 Zotero MCP 服务](https://www.bibgenie.com/zh/docs/mcp)
- [Zotero 联动 Notion 工作流](https://www.bibgenie.com/zh/docs/zotero-to-notion)
- [套餐与 Credit 机制说明](https://www.bibgenie.com/zh/docs/pricing-credits)

---

## 关于本仓库

本仓库为 BibGenie 官方产品信息发布与版本下载地址。BibGenie 应用程序的源代码不在本仓库中公开发布。

## 支持与交流

- 官网：[www.bibgenie.com](https://www.bibgenie.com/zh)
- 帮助文档：[www.bibgenie.com/zh/docs](https://www.bibgenie.com/zh/docs)
- Discord 社区：[加入官方社群](https://discord.gg/kDXFAAYDNE)
- 邮箱反馈：[support@bibgenie.com](mailto:support@bibgenie.com)

<div align="center">
  <strong>让你的 Zotero 文献库进入 AI 原生研究工作流。</strong>
  <br/><br/>
  <a href="https://www.bibgenie.com/zh/download"><strong>下载 BibGenie</strong></a>
</div>
