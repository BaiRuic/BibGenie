<div align="center">
  <img src="public/logo.png" alt="BibGenie Logo" width="120"/>
  
  # BibGenie
  
  ### 🧞 您的 Zotero 智能 AI 助手
  
  [English](README_EN.MD) | 简体中文
  
  [![Zotero](https://img.shields.io/badge/Zotero-7-red.svg)](https://www.zotero.org/)
  [![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da.svg)](https://discord.gg/kDXFAAYDNE)
  [![Website](https://img.shields.io/badge/Website-bibgenie.com-blue.svg)](https://www.bibgenie.com)
  
  **BibGenie 是一款强大的 Zotero AI 助手插件，帮助研究人员理解 PDF 文献、回答研究问题、提升科研效率。**
  
  **🌐 更多信息请访问官方网站：[www.bibgenie.com](https://www.bibgenie.com)**
  
  [下载插件](#-安装) · [加入 Discord](https://discord.gg/kDXFAAYDNE)
  
</div>

---

## ✨ 核心特性

### 🤖 多模型支持
与 ChatGPT、Claude、Gemini、DeepSeek、Qwen、Kimi 等多个 AI 模型无缝集成，选择最适合您研究需求的 AI 模型。

- ✅ **OpenAI (ChatGPT)** - GPT-4, GPT-3.5
- ✅ **Anthropic (Claude)** - Claude 3.5 Sonnet, Claude 3 Opus
- ✅ **Google (Gemini)** - Gemini Pro, Gemini Ultra
- ✅ **DeepSeek** - DeepSeek Chat, DeepSeek Coder
- ✅ **Alibaba (Qwen)** - 通义千问系列
- ✅ **Moonshot (Kimi)** - Kimi Chat
- ✅ **Ollama** - 本地模型支持
- ✅ **OpenRouter** - 统一 API 接入

### 🎯 与 Zotero 深度集成

<table>
  <tr>
    <td width="50%">
      <h4>📋 快捷键操作</h4>
      <ul>
        <li><kbd>Ctrl</kbd> + <kbd>L</kbd> 快速打开聊天对话框</li>
        <li><kbd>Ctrl</kbd> + <kbd>V</kbd> 直接粘贴图片到对话框</li>
        <li>无需手动导入，流畅的研究体验</li>
      </ul>
    </td>
    <td width="50%">
      <h4>📚 智能上下文管理</h4>
      <ul>
        <li>一键添加当前阅读的 PDF 到 LLM 上下文</li>
        <li>搜索并添加文库中的任意 PDF 附件</li>
        <li>无需手动复制粘贴，自动提取内容</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>💬 对话历史管理</h4>
      <ul>
        <li>保存所有聊天记录</li>
        <li>一键继续之前的对话</li>
        <li>方便回顾研究思路</li>
      </ul>
    </td>
    <td width="50%">
      <h4>⚡ Prompt 快捷管理</h4>
      <ul>
        <li>内置 Prompt 模板库</li>
        <li>支持自定义 Prompt</li>
        <li>快捷输入，提升效率</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📸 产品截图

<div align="center">

### 主界面 - 与 Zotero 完美融合
<img src="public/blocks/main-page(empty-1440x1108).png" alt="BibGenie 主界面" width="800"/>

### 快捷键操作 - Ctrl+L 打开对话框
<img src="public/blocks/main-page(shoctcut-1440x1108).png" alt="快捷键操作" width="800"/>

### 图片输入支持 - Ctrl+V 粘贴图片
<img src="public/blocks/main-page(image-input-support-1440x1108).png" alt="图片输入支持" width="800"/>

### 添加上下文 - 智能 PDF 管理
<img src="public/blocks/main-page(add-context-1440x1108).png" alt="添加上下文" width="800"/>

### 多模型支持 - 自由切换 AI 模型
<img src="public/blocks/main-page(multi-llm-support-1440x1108).png" alt="多模型支持" width="800"/>

### 对话历史 - 回顾研究思路
<img src="public/blocks/main-page(chat-history-view-1440x1108).png" alt="对话历史" width="800"/>

### Prompt 管理 - 快捷输入模板
<img src="public/blocks/main-page(prompt-snippet-1440x1108).png" alt="Prompt 管理" width="800"/>

</div>

---

## 🚀 安装

### 系统要求
- **Zotero 7** (目前仅支持 Zotero 7，Zotero 8 支持正在开发中)
- Windows / macOS / Linux

### 安装步骤

1. **下载插件**
   - 前往 [Releases](https://github.com/BaiRuic/BibGenie/releases) 页面
   - 下载最新版本的 `.xpi` 文件

2. **安装到 Zotero**
   - 打开 Zotero
   - 进入 `工具` → `插件`
   - 点击右上角齿轮图标 ⚙️
   - 选择 `Install Add-on From File...`
   - 选择下载的 `.xpi` 文件
   - 重启 Zotero

---

## ❓ 常见问题

<details>
<summary><strong>是否提供免费试用？</strong></summary>
<br>
对于免费用户，我们提供永久免费使用权限。您只需要配置自己的 AI 模型 API Key 即可使用。
</details>

<details>
<summary><strong>支持哪些文档格式？</strong></summary>
<br>
目前仅支持 PDF 附件。其他文件类型的支持正在开发中，即将推出。
</details>

<details>
<summary><strong>BibGenie 如何安全访问我的研究论文？</strong></summary>
<br>
BibGenie 通过官方安全 API 连接到您的 Zotero 文库。您的研究数据完全私密和安全，存储在您的本地设备上。我们从不上传您的研究内容或索引到外部服务器。
</details>

<details>
<summary><strong>可以集成自己的 AI 模型和 API 吗？</strong></summary>
<br>
当然可以！BibGenie 支持自定义 LLM 配置，您可以使用自己的 API Host 和 Key 设置多个 AI 模型。您可以在研究过程中无缝切换不同模型以获得最佳效果。
</details>

<details>
<summary><strong>支持哪些版本的 Zotero？</strong></summary>
<br>
目前仅支持 Zotero 7。Zotero 8 的支持正在开发中，即将推出。
</details>

<details>
<summary><strong>在哪里可以获得帮助和支持？</strong></summary>
<br>
加入我们活跃的 Discord 社区，我们的开发团队和研究人员同行随时准备提供帮助。
</details>

---

## 📞 联系我们

- **Discord 社区**: [加入我们](https://discord.gg/kDXFAAYDNE)
- **官方网站**: [www.bibgenie.com](https://www.bibgenie.com)
- **邮箱**: support@bibgenie.com

---

<div align="center">
  
  **用 BibGenie 开启您的智能研究之旅** 🚀
  
  [立即下载](https://github.com/BaiRuic/BibGenie/releases) · [访问官网](https://www.bibgenie.com) · [加入社区](https://discord.gg/kDXFAAYDNE)
  
  ---
  
  Made with ❤️ by the BibGenie Team
  
</div>
