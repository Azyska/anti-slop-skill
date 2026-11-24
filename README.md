<div align="center">

# 🚫 Anti-Slop Skill

**Strict System Ruleset to Eliminate AI Fluff, Filler Text, and Lazy Code Placeholders**

![Type](https://img.shields.io/badge/Type-AI_Agent_Skill-1E1E2E?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-Markdown-3776AB?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA043?style=for-the-badge)

</div>

---

## 📋 Overview

**Anti-Slop Skill** is a drop-in instruction ruleset designed for AI coding assistants and LLM workflows. It strips away robotic greetings, bloated summaries, buzzword filler, and lazy `# TODO` code stubs—forcing models to deliver direct, production-ready answers immediately.

## ✨ What It Blocks

- **Text Slop:** Eliminates *"Certainly! Here is..."*, *"Hope this helps!"*, and redundant closing summaries.
- **Buzzword Padding:** Bans hollow adjectives (*seamless*, *robust*, *comprehensive*) in favor of concrete technical details.
- **Code Laziness:** Prohibits truncated code snippets (`// ... existing code`) and unnecessary third-party dependencies.

---

## 📖 How to Use

### 1. Clone the Repository
```bash
git clone [https://github.com/Azyska/anti-slop-skill.git](https://github.com/Azyska/anti-slop-skill.git)
cd anti-slop-skill
```

### 2. Apply to Your AI Workflow
- **Cursor / Windsurf:** Copy `.cursorrules` into the root of your project repository.
- **Claude Code / Custom Agents:** Reference `SKILL.md` in your `CLAUDE.md` or agent system prompt.
- **Chat Interfaces (Gemini / ChatGPT):** Paste the contents of `SKILL.md` into your Custom Instructions or Gem system prompt.

---

## 📂 Project Structure

```text
anti-slop-skill/
├── SKILL.md        # Core anti-slop instruction ruleset
├── .cursorrules    # Ready-to-use rules file for AI code editors
├── LICENSE         # MIT License
└── README.md       # Documentation & integration guide
```

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.
