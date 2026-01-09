```markdown
# Global Agent Skills

## English

This repository contains my **personal global skills collection** for AI agents, designed to be reused across
**Codex CLI**, **Claude**, and **IDE-based agents (e.g. VSCode)**.

Skills in this repository are organized, adapted, and versioned for **personal productivity and experimentation**.

---

### 📍 Installation Location

```text
~/.agent/skills
```

This directory is automatically scanned by agent runtimes that support the
**universal-skills MCP protocol**.

---

### 🔌 How Skills Are Loaded

- Loaded via: **universal-skills MCP**
- Usable in:
  - Codex CLI
  - Codex VSCode Extension
  - Other MCP-compatible agent environments

Once installed, skills are globally available to all projects on the local machine.

---

### 📦 References & Attribution

This repository is maintained for **personal use** and is inspired by and references the following open-source projects:

- **Anthropic Skills Repository**  
  https://github.com/anthropics/skills

- **Universal Skills (MCP-based skill loader)**  
  https://github.com/klaudworks/universal-skills

Some skills or structural patterns in this repository may be inspired by or adapted from these upstream projects.
All original rights and licenses remain with their respective authors.
Please refer to the upstream repositories for detailed licensing information.

---

### 🧠 Design Philosophy

- Skills are **model-agnostic** and **tool-oriented**
- Each skill:
  - Lives in its own directory
  - Contains a `SKILL.md` file
  - Is loaded lazily (only when relevant)
- Descriptions are optimized for accurate skill matching in agent environments

---

### 🛠️ Repository Structure

```text
~/.agent/skills/
├── <skill-name>/
│   └── SKILL.md
├── <another-skill>/
│   └── SKILL.md
└── README.md
```

---

### 🚀 Usage

In Codex or other supported agents, you can trigger a skill by explicitly saying:

> “Use the **<skill-name>** skill to …”

Or by clearly describing a task that matches the skill description.

---

### 📖 Notes

- This repository is intended for **personal use only**
- Skills may evolve over time and may diverge from upstream ideas or implementations
- Contributions are currently not accepted

---

## 中文说明

本仓库用于存放我个人维护的 **全局 Agent Skills（技能库）**，主要用于
**个人效率提升与实验探索**。

这些技能可在多个 Agent 环境中复用，包括：

- Codex CLI
- Claude
- VSCode 等 IDE 内的 Agent

---

### 📍 安装位置

```text
~/.agent/skills
```

该目录会被支持 **universal-skills MCP 协议** 的 Agent 运行时自动扫描。

---

### 🔌 技能加载方式

- 加载方式：**universal-skills MCP**
- 可用环境：
  - Codex CLI
  - Codex VSCode 扩展
  - 其他兼容 MCP 的 Agent 系统

安装后，技能将在本机范围内对所有项目全局可用。

---

### 📦 参考来源与说明

本仓库为 **个人使用项目**，在设计与实现过程中参考了以下开源项目：

- **Anthropic 官方 Skills 仓库**  
  https://github.com/anthropics/skills

- **Universal Skills（基于 MCP 的技能加载器）**  
  https://github.com/klaudworks/universal-skills

仓库中的部分技能结构、组织方式或设计理念可能受到上述项目的启发，
并根据个人使用场景进行了调整。

所有原始版权与许可均归原作者所有，
具体授权条款请参考对应的上游仓库说明。

---

### 🧠 设计理念

- 技能是 **模型无关（model-agnostic）**、**工具优先（tool-first）** 的
- 每个技能：
  - 位于独立目录
  - 包含一个 `SKILL.md`
  - 仅在与当前任务匹配时按需加载
- 技能描述针对 Agent 的匹配机制进行了优化

---

### 🛠️ 仓库结构示例

```text
~/.agent/skills/
├── <skill-name>/
│   └── SKILL.md
├── <another-skill>/
│   └── SKILL.md
└── README.md
```

---

### 🚀 使用方式

在 Codex 或其他支持的 Agent 中，可以通过以下方式触发技能：

- “使用 **<skill-name>** skill 来……”
- 或直接描述清楚任务需求，Agent 会根据技能描述自动匹配

---

### 📖 说明

- 本仓库主要用于 **个人使用与实验目的**
- 技能内容可能随时间演进，并不保证与上游项目保持一致
- 当前不接受外部贡献
```
