<div align="center">
  <img src="./public/logo.png" alt="BibGenie logo" width="112"/>

  # BibGenie

  ### Zotero 内的 AI 研究智能体

  [English](README.MD) | [简体中文](README_ZH.MD)

  [![Zotero 7, 8 and 9](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209-cc2936)](https://www.zotero.org/)
  [![官网](https://img.shields.io/badge/Website-bibgenie.com-2563eb)](https://www.bibgenie.com/zh)
  [![文档](https://img.shields.io/badge/Docs-开始使用-0f766e)](https://www.bibgenie.com/zh/docs)
  [![Discord](https://img.shields.io/badge/Discord-Community-5865f2)](https://discord.gg/kDXFAAYDNE)

  **BibGenie 原生运行在 Zotero 中，围绕你的论文、笔记、网页快照、图片和文库结构工作。添加研究上下文，提出有依据的问题，检索并整理文献库，再把有价值的结果保存回 Zotero 笔记。**

  [免费下载插件](https://www.bibgenie.com/zh/download) · [查看文档](https://www.bibgenie.com/zh/docs) · [加入 Discord](https://discord.gg/kDXFAAYDNE)
</div>

---

## 原生的 Zotero 研究工作流

BibGenie 不是一个需要你把研究材料搬出 Zotero 的独立网页聊天工具。它是位于 Zotero 侧边栏中的 AI research agent，围绕你现有的文献材料和整理方式工作。

1. **添加上下文**：插入 Zotero item、PDF attachment、网页快照、note、选中文字、当前页面、图片、截图、tag 或 collection。
2. **提问与检索**：阅读论文、解释公式和图表、检索文献库、对比多篇文章，或综合一个文献集合。
3. **整理与沉淀**：将回答保存为 Zotero note，并以可审核的方式整理 tag、collection 与元信息。

<p align="center">
  <img src="./public/blocks/demo-workflow.gif" alt="BibGenie 在 Zotero 内添加上下文、围绕论文提问并保存结果的工作流" width="860"/>
  <br/>
  <sub>完整研究工作流预览：添加上下文、阅读论文、保存结果。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/add_context_read_save_lq.mp4">查看高清原视频</a></sub>
</p>

## 核心功能

### 添加任意 Zotero 上下文

无需把研究材料复制到独立聊天工具中，直接把你的 Zotero 工作区带入对话：

- 使用 `@` 或 Zotero 中的 **Add to Chat** 入口添加 item、PDF、note、snapshot、tag 与 collection。
- 添加选中文字、当前页面、图表、粘贴图片与截图。
- 基于当前论文、项目或文献集合提出有依据的问题。

<p align="center">
  <img src="./public/blocks/demo-at-context.gif" alt="在 BibGenie 中使用 @ 菜单添加 Zotero 上下文" width="760"/>
  <br/>
  <sub>使用 <code>@</code> 添加 Zotero 材料。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/at_any_context.mp4">查看高清原视频</a></sub>
</p>

图表和截图同样可以作为上下文。你可以在 Zotero reader 中直接让 BibGenie 解释图示、公式或页面区域。

<p align="center">
  <img src="./public/blocks/demo-explain-image.gif" alt="BibGenie 解释 Zotero PDF 中选取的图表" width="760"/>
  <br/>
  <sub>讨论 reader 中的图表与截图。<a href="https://cfr2.bibgenie.com/bibgenie-mp4s/explain_image.mp4">查看高清原视频</a></sub>
</p>

### 检索、阅读并综合你的文献库

- 按标题、作者、年份、DOI、tag、collection、期刊或会议检索文献。
- 基于本地 Zotero 标题和摘要索引进行语义检索。
- 精读论文、比较多篇文章、生成结构化表格，并将有价值的结果保存为 Zotero note。

<p align="center">
  <img src="./public/blocks/search_paper_compres.png" alt="BibGenie 检索并阅读 Zotero 文献库中的论文" width="860"/>
</p>

### 整理你的 Zotero 文献库

- 检查并整理 tag、collection、文献移动和 metadata。
- 对于敏感的批量操作，先让 BibGenie 给出计划，确认受影响条目后再明确执行。

<p align="center">
  <img src="./public/blocks/organize_library_compress.png" alt="BibGenie 以先预览后执行的方式整理 Zotero 文献库" width="860"/>
</p>

### 选择适合研究环境的模型配置

- 直接使用 BibGenie 官方模型选项；第一次提问无需配置 API Key。
- 使用自己的 Key 接入 OpenAI、Anthropic、DeepSeek、Gemini、OpenRouter、Groq 或 OpenAI-compatible endpoint。
- 使用 Ollama 或 LM Studio 进行本地推理。自定义模型与本地模型请求会直接发往你配置的 provider 或 runtime。

### 通过联网研究与 Zotero MCP 扩展工作流

- 付费套餐提供 **Web Search** 与 **Web Extract**，用于读取文库之外的公开网页资料。
- 内置的本地 **Zotero MCP** server 可让 Cursor、Claude Code、Claude Desktop、Cherry Studio 等支持 MCP 的客户端使用 Zotero 上下文。
- 受信任的外部客户端可通过 MCP 在本地检索 item、读取附件或 snapshot、创建 note，并管理文库 metadata。

## 安装 BibGenie

### 系统要求

- Zotero 7、Zotero 8 或 Zotero 9
- Windows、macOS 或 Linux

### 安装步骤

1. 从 [BibGenie 下载页](https://www.bibgenie.com/zh/download) 或 [GitHub Releases](https://github.com/BaiRuic/BibGenie/releases) 下载最新 `.xpi` 插件。
2. 在 Zotero 中打开 **Tools -> Plugins**。
3. 点击齿轮图标，选择 **Install Plugin From File...**。
4. 选择 `bibgenie-<version>.xpi`，然后重启 Zotero。
5. 从 Zotero 工具栏或 **Tools -> BibGenie** 打开 BibGenie。

BibGenie 会在 Zotero 启动时检查更新；你也可以在 Zotero Plugin Manager 中为 BibGenie 开启自动更新。

## 套餐与隐私

- **Free** 包含 Zotero 核心研究智能体、上下文工具、文库检索、Save as Note、自定义模型以及每月官方模型 Credit。
- **Pro / Max / Lifetime** 提供更多官方模型额度；付费套餐包含 Web Search / Web Extract。
- **BYOK 与本地模型** 不消耗 BibGenie 官方模型 Credit，相关 provider 费用或本地算力由用户承担。
- 对话记录默认保存在 Zotero 本地数据库中。使用自定义模型或本地模型时，请求直接发往配置的 provider 或 runtime。

当前套餐价格和 Credit 详情以官网 [Pricing 页面](https://www.bibgenie.com/zh/pricing) 与[文档](https://www.bibgenie.com/zh/docs/pricing-credits)为准。

## 了解更多

- [快速开始](https://www.bibgenie.com/zh/docs/getting-started)
- [添加上下文](https://www.bibgenie.com/zh/docs/add-context)
- [文献检索](https://www.bibgenie.com/zh/docs/literature-search)
- [模型与 BYOK](https://www.bibgenie.com/zh/docs/models)
- [Zotero MCP](https://www.bibgenie.com/zh/docs/mcp)

## 关于本仓库

本仓库用于公开展示 BibGenie 产品信息并提供可下载版本。BibGenie 应用程序的源代码不在本仓库中公开。

## 支持

- 官网：[www.bibgenie.com](https://www.bibgenie.com/zh)
- 文档：[www.bibgenie.com/zh/docs](https://www.bibgenie.com/zh/docs)
- Discord：[加入社区](https://discord.gg/kDXFAAYDNE)
- 邮箱：[support@bibgenie.com](mailto:support@bibgenie.com)

<div align="center">
  <strong>让你的 Zotero 文献库进入 AI 原生研究工作流。</strong>
  <br/><br/>
  <a href="https://www.bibgenie.com/zh/download"><strong>下载 BibGenie</strong></a>
</div>
