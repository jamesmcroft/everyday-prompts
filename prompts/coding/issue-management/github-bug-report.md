---
title: GitHub Bug Report
category: coding
subcategory: issue-management
description: Turn a short problem summary into a formatted GitHub bug ticket using a consistent template.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Brief description of the issue
  - Detailed reproduction steps
  - Expected vs. actual behavior
---

# GitHub Bug Report

Use this prompt when you want the model to draft a clean GitHub issue that matches your bug template. It is especially helpful when you know the reproduction steps and just need consistent formatting before sharing with maintainers.

## Prompt

```text
Generate a GitHub bug report for "<describe issue>".

<Detailed description of how the issue can be reproduced>.

Use the following issue template:

- Title: "[Bug]: ..."
- Steps to reproduce: "Describe accurately how we can reproduce/verify the bug"
- Expected behavior: "A clear and concise description of what you expected to happened"
- Actual behavior: "A clear and concise description of what actually happened"
```

> [!TIP]
> Replace the placeholders with your actual description and reproduction steps. Copilot or ChatGPT will fill in the issue sections, which you can then paste into your repository.
