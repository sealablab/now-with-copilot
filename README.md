# 🚀 forge-vhdl: AI-Powered VHDL Development in Minutes

**Build tested VHDL components in 2-5 minutes with AI assistance.**

[![Use This Template](https://img.shields.io/badge/Use%20This%20Template-2ea44f?style=for-the-badge&logo=github)](../../generate)

---

## 🤖 Choose Your AI Workflow

**GitHub Copilot Edition** ⭐ **NEW!**
- ✅ IDE-integrated (VS Code, JetBrains)
- ✅ Inline suggestions & chat-based development
- ✅ File-focused iterative workflow
- 📖 **[Read COPILOT.md](COPILOT.md)** for Copilot-optimized guide

**Claude Edition** (Original)
- ✅ Autonomous 3-agent workflow
- ✅ Multi-file context and generation
- ✅ Requirements gathering interviews
- 📖 **[Read CLAUDE.md](CLAUDE.md)** for Claude-optimized guide

**Hybrid Approach** (Recommended)
- Use **Claude** for requirements & specs
- Use **Copilot** for implementation & testing
- Use **Claude** for autonomous batch operations
- Use **Copilot** for iterative debugging

---

## 🎬 See It In Action

**Watch the complete workflow in 3 minutes:**

[![asciicast](https://asciinema.org/a/O7T8zh2OPdbqEMX84TjfNnu9p.svg)](https://asciinema.org/a/O7T8zh2OPdbqEMX84TjfNnu9p)

**What you'll see:**
- 💻 Interactive requirements gathering (2 questions, 30 seconds)
- 🤖 AI agent generating VHDL specification
- ✅ Complete component ready for cloud execution
- 📦 From idea to specification in under 3 minutes

**[▶️ Click to watch the recording](https://asciinema.org/a/O7T8zh2OPdbqEMX84TjfNnu9p)**

---

## ⚡ Quick Start

### For GitHub Copilot Users

```bash
# 1. Setup
uv run python .claude/env_detect.py
uv sync

# 2. Open in your IDE (VS Code, JetBrains)
code .

# 3. Ask Copilot in chat
# "@workspace I need a PWM generator. 
#  Use the AI-First requirements workflow."
```

**Read [COPILOT.md](COPILOT.md) for IDE-optimized workflows**

### For Claude Users

```bash
/forge-start
```

![Claude CLI Running](static/Local-CLI-Running-user-input.png)

**That's it!** Answer 2-5 questions → Get tested VHDL → Done in minutes.

**Read [CLAUDE.md](CLAUDE.md) for autonomous workflows**

---

## 🔄 Development Workflows

### 🚀 AI-First (DEFAULT - 2-5 Minutes)

**Best for:** Students, quick prototyping, learning

**With Copilot:**
```
@workspace I need a [component]. Use the AI-First requirements workflow
to generate a spec, then create VHDL + P1 tests.
```

**With Claude:**
```
/forge-start
> Choose: AI-First Workflow
> Answer: 2-3 critical questions
> Get: Tested VHDL component
```

**Time:** 2-5 minutes  
**Guide:** `workflow/AI_FIRST_REQUIREMENTS.md`

### 🔧 Engineer (Advanced - 15-30 Minutes)

**Best for:** Complex systems, full control, detailed specs

**With Copilot:**
```
@workspace Read workflow/ENGINEER_REQUIREMENTS.md and guide me
through the requirements process for [component].
```

**With Claude:**
```
/forge-start
> Choose: Engineer Workflow
> Answer: 30-question structured interview
> Get: Production-ready component
```

**Time:** 15-30 minutes  
**Guide:** `workflow/ENGINEER_REQUIREMENTS.md`

---

## 📄 License & Info

**License:** MIT License - See `LICENSE` file

**Version:** 3.2.0
**Template:** https://github.com/vmars-20/forge-vhdl-3v3-vmars
**Your Repository:** 🔧 **UPDATE THIS** → `https://github.com/YOUR-USERNAME/YOUR-REPO-NAME`
**Last Updated:** 2025-11-09
**Maintainer:** Moku Instrument Forge Team
