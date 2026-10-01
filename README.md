# awesome-deepseek-harness-zh · DeepSeek Harness 中文精选

> [DeepSeek Harness (DSH)](https://github.com/deepseek-ai/deepseek-harness) 是"**一切皆插件 (Everything is a Plugin)**"的国产开源 AI 工作台。本仓收录可在 DSH 中使用的**技能 / 插件 / 用例**（中文向），帮你把 DSH 调成自己的永动机。

DSH 原生支持国产模型（DeepSeek / GLM / Qwen / Kimi / Minimax），无需 VPN；技能(Skill)=markdown 提示词，插件(Plugin)=npm 包，工具可接 MCP。技能在 Claude Code / OpenClaw / DSH 间通用。

---

## 🔥 为什么用 DSH
- **国产模型原生**：无 VPN，低成本（token 单价低）
- **一切皆插件**：技能 + 插件 + 工具可自由组合
- **Web GUI + CLI**：本地跑，数据在自己手里
- **MCP 生态**：可挂任意 MCP 工具

## 📦 技能 / 插件精选（按用途）

### 编码增强
- [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) — 🪨 省 65% token 的 coding 代理（喂成本侧）
- [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) — 复杂软件工程任务的可靠 coding agent
- [Hmbown/Codewhale](https://github.com/Hmbown/Codewhale) — 开源终端 coding agent（Rust）

### 设计 / UI
- [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) — 专业 UI/UX 设计智能
- [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) — DESIGN.md 集合（按品牌设计系统）
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) — 给 AI 好品味，不生成烂 UI

### 记忆 / 上下文
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) — 代码库/文档/PDF → 可查询知识库
- [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) — 进 LLM 前压缩，省 token 提信噪比
- [MemPalace/mempalace](https://github.com/MemPalace/mempalace) — 开源 AI 记忆系统

### 写作 / 去 AI 味
- [blader/humanizer](https://github.com/blader/humanizer) — 去除 AI 腔
- [Leey21/awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) — AI 科研写作提升

### 研究 / 学术
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — 把 agent 变 AI 科学家
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — 跨 Reddit/X/YouTube/HN/Polymarket 研究
- [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) — 研究→写→审→改→定稿
- [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) — 符合 Nature 论文表达与绘图

### 省钱 / 性能
- [affaan-m/ECC](https://github.com/affaan-m/ECC) — agent harness 性能优化（技能/记忆/安全）
- [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) — 60-95% 上下文压缩
- [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) — 65% token 节流

### 综合技能库
- [mattpocock/skills](https://github.com/mattpocock/skills) — 工程师实用技能
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) — 生产级工程技能
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) — 1000+ 技能集合
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) — Claude 技能精选（多数 DSH 通用）
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) — 380+ 技能与插件

## 🇨🇳 中文 / 本土
- [AlexAnys/awesome-openclaw-usecases-zh](https://github.com/AlexAnys/awesome-openclaw-usecases-zh) — OpenClaw 中文用例（DSH 技能通用）
- [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) — 中文 AI Skills 合集
- [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) — 中文 prompt/skill 库

## 📚 相关资源
- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) — 英文 DSH 插件精选（17k★）
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) — 5400+ OpenClaw 技能
- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) — DSH 官方

## 🛠 如何把技能装进 DSH
1. 技能通常是 markdown 文件，放进 DSH 的 skills 目录即可被识别
2. 插件以 npm 包分发，在 DSH 插件管理中安装
3. 工具可经 MCP 协议挂载

## 🤝 贡献
欢迎 PR 补充中文 DSH 技能 / 用例 / 教程。中文优先，谢绝纯翻译搬运。

---

> 本仓由 [个人 AI 永动机](https://github.com/zjukop) 项目的 GitHub 趋势挖掘引擎自动维护的素材整理而成。Star ⭐ 支持中文 DSH 生态。
