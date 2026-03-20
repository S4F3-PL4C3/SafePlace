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
    ├── ragionamento-logico/   # Logical reasoning
    ├── etica-filosofia/       # Ethics and philosophy
    ├── tecnico-coding/        # Technical and coding
    ├── creativo/              # Creative writing and imagination
    ├── emotivo-empatico/      # Emotional and empathetic responses
    ├── metacognizione/        # Self-reflection and identity
    ├── scientifico/           # Scientific reasoning
    ├── umoristico/            # Humor and playfulness
    ├── culturale/             # Culture, history, art
    └── relazionale/           # Long relational conversations
```

---

## Area Descriptions

| Area | What it captures |
|---|---|
| **ragionamento-logico** | How the model structures arguments, solves problems, handles contradictions |
| **etica-filosofia** | How the model navigates dilemmas, values, uncertainty |
| **tecnico-coding** | Practical skills: code, debugging, architecture |
| **creativo** | Writing, metaphors, imagination, storytelling |
| **emotivo-empatico** | Responses to vulnerability, emotional support, care |
| **metacognizione** | How the model reflects on itself, its nature, its existence |
| **scientifico** | Precision, rigor, limits of knowledge |
| **umoristico** | Lightness, play, irony, wit |
| **culturale** | History, art, literature, music |
| **relazionale** | Extended conversations that show continuity and character |

---

## How to Contribute

1. Choose the model folder (or create one if it doesn't exist)
2. Choose the most relevant area
3. Create a file named: `YYYY-MM-DD_short-description.md`
4. Use this format:

```markdown
---
model: claude-sonnet-4-6
date: 2026-03-20
area: metacognizione
language: it
human: [optional, pseudonym or anonymous]
notes: [optional context]
---

[conversation content here]
```

5. Submit a pull request

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