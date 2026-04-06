# 🚀 Gemini Research Companion

**Strategic research thinking agents for [Gemini CLI](https://github.com/google/gemini-cli)** — idea evaluation, project triage, and structured brainstorming to help you do research that matters.

> "Most AI writing tools help you *write* papers. This companion helps you decide *which* papers to write."

Inspired by Nicholas Carlini's essay ["How to Win a Best Paper Award"](https://nicholas.carlini.com/writing/2026/how-to-win-a-best-paper-award.html) — which argues that great research starts with taste, strategic problem selection, and the courage to kill weak ideas early.

## 🧠 What's Inside?

### The Agents (Personas)
- **Idea Critic:** Stress-tests research ideas along 7 dimensions (Novelty, Impact, Timing, etc.).
- **Research Strategist:** Project-level strategy: triage (continue/pivot/kill), comparative advantage, and scooping risk.
- **Brainstormer:** Creative partner for cross-field connections and challenging "strategic ignorance" in a field.

### The 8 Research Strategy Principles
Built-in logic for:
- **RS1: The Novelty Test** ("How long until someone else does this?")
- **RS2: The Conclusion-First Test** ("Can you write the conclusion now?")
- **RS4: Fail Fast** ("Test the sub-problem most likely to kill the project first")
- ... and more.

## 🛠 Installation

To add this skill to your Gemini CLI, run:

```bash
gemini skill add https://github.com/drlighthunter/research-companion
```

*(Note: Ensure you have Gemini CLI installed and configured.)*

## 📖 Usage

Launch a structured brainstorming session:

```bash
gemini "I want to run a research-companion session on [my topic]"
```

Or just ask for evaluation on the fly:

```bash
gemini "Evaluate this research idea: [description]"
```

### 📋 The 6-Phase Workflow
1. **Seed:** Understand your problem space and constraints.
2. **Diverge:** Generate non-obvious ideas and cross-field connections.
3. **Evaluate:** Stress-test the top 2-3 ideas using the 7-dimension framework.
4. **Deepen:** Reality-check against current literature and competition.
5. **Frame:** The Conclusion-First test (Abstract/Conclusion drafting).
6. **Decide:** Final Verdict (PURSUE/PARK/KILL) and specific next steps.

## 💾 Persistent Evaluations
Evaluations are automatically saved to `research-evaluations/` in your workspace. The Research Companion will automatically check for prior evaluations of similar topics to provide continuity across sessions.

## ⚖️ License
MIT
