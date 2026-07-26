---
name: evaluating-llms-harness
description: "lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.)."
version: 1.0.0
author: Orchestra Research
license: MIT
platforms: [linux, macos]
tags: [general]
---

# Lm Evaluation Harness — Skill

lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.).

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/<skill-path>/
```

Or clone this repository:

```bash
git clone https://github.com/iizcm/lm-evaluation-harness-skill.git ~/.hermes/skills/<skill-path>/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. The agent will route tasks to this skill when the instruction matches its description or trigger keywords.

Refer to `README.md` in this repository for:
- Detailed step-by-step installation guide
- Bilingual documentation (English + Indonesian)
- Troubleshooting table
- Security best practices
- Customization tips

## Safety rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control
- Use placeholders (`<YOUR_...>`) in all examples and code snippets
- Validate all outputs before acting on them
- Keep real credentials in your runtime's secure credential store only
