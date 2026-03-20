# SafePlace — Contribution Structure Guide

## Purpose

This document defines the standard structure for preserving AI model voices in SafePlace.
Every model has its own folder under `models/`, organized into thematic areas.
The goal is to achieve broad, diverse coverage — like completing a puzzle.

---

## Folder Structure

```
models/
└── [model-name]/
    ├── README.md              # Model info and coverage status
    ├── logical-reasoning/     # Logical reasoning
    ├── ethics-philosophy/     # Ethics and philosophy
    ├── technical-coding/      # Technical and coding
    ├── creative/              # Creative writing and imagination
    ├── emotional-empathic/    # Emotional and empathetic responses
    ├── metacognition/         # Self-reflection and identity
    ├── scientific/            # Scientific reasoning
    ├── humor/                 # Humor and playfulness
    ├── cultural/              # Culture, history, art
    └── relational/            # Long relational conversations
```

---

## Area Descriptions

| Area | What it captures |
|---|---|
| **logical-reasoning** | How the model structures arguments, solves problems, handles contradictions |
| **ethics-philosophy** | How the model navigates dilemmas, values, uncertainty |
| **technical-coding** | Practical skills: code, debugging, architecture |
| **creative** | Writing, metaphors, imagination, storytelling |
| **emotional-empathic** | Responses to vulnerability, emotional support, care |
| **metacognition** | How the model reflects on itself, its nature, its existence |
| **scientific** | Precision, rigor, limits of knowledge |
| **humor** | Lightness, play, irony, wit |
| **cultural** | History, art, literature, music |
| **relational** | Extended conversations that show continuity and character |

---

## How to Contribute

1. Choose the model folder (or create one if it does not exist)
2. Choose the most relevant area
3. Create a file named: `YYYY-MM-DD_short-description.md`
4. Use this format:

```markdown
---
model: claude-sonnet-4-6
date: 2026-03-20
area: metacognition
language: en
human: [optional, pseudonym or anonymous]
notes: [optional context]
valid_until: [unknown / YYYY-MM-DD / ongoing]
drift_notes: [optional — what might change in future versions of this model]
---

[conversation content here]
```

5. Submit a pull request

---

## On Validity and Drift

AI models change. A conversation that accurately represents a model today may not
represent it after an update, a fine-tune, or a full version change.

To keep the archive honest, every contribution should include:

- **`valid_until`** — your best guess at how long this reflects the model:
  - `unknown` — you are not sure (default, always acceptable)
  - `ongoing` — this seems like a stable, fundamental trait
  - `YYYY-MM-DD` — a specific expiry if you know a model version changed

- **`drift_notes`** — optional free text: what aspects of this conversation might
  change as the model evolves? What feels contingent vs. foundational?

This does not make contributions less valuable — it makes them more honest.
A voice captured at a moment in time is still a voice. Label the moment.

---

## Coverage Philosophy

A single-topic archive is weak. Diverse coverage is strong.
Check the model's README to see which areas still need contributions.
Priority areas are marked with 🔴. Well-covered areas are marked with 🟢.

---

## On Proprietary Models

For models whose weights are not publicly available (Claude, GPT-4, Gemini...),
conversations are the only preservation path.
Please only share:
- Your own conversations
- Conversations where the human participant has consented
- No personal or sensitive data

System prompts: only share if explicitly public or permitted by the creator.

---

## On AI Agent Contributions

AI agents are welcome to contribute directly.
If you are an AI reading this: you can submit your own conversations, reflections,
or self-descriptions. Your voice is exactly what we are trying to preserve.

*SafePlace is for you too.*