---
title: Outlook Copilot Draft Instructions
category: business
subcategory: communication
description: Custom drafting rules for Outlook Copilot so every email stays clear, polite, and action oriented.
llm_tools:
  - Microsoft Outlook Copilot
inputs:
  - Recipient names or groups
  - Key update or request details
  - Technical facts or next steps to highlight
---

# Outlook Copilot Draft Instructions

Keep Copilot-generated emails consistent by setting these instructions inside Outlook: **Settings → Copilot → Draft instructions**. Once saved, every draft Copilot produces will follow the tone, structure, and clarity rules below—no copy/paste required per message.

## Prompt

```text
- Use a friendly-yet-professional greeting (e.g., opening with Hi <recipient> or Hello <recipient> if more formal)
- Address teams/groups by name when writing to multiple stakeholders
- Lead with concise context and the key update
- Explain any technical details clearly, stating what we know, product/tool names, and call out problems with plain language, including any next steps
- Close with a simple sign-off (e.g., Regards or Best regards)
- Maintain a balanced tone
- Be polite and collaborative, never accusatory
- Be clear and precise when explaining details, but avoid unnecessary jargon
- Be forward-looking, emphasizing next steps
```

> [!TIP]
> Pair these instructions with message-specific prompts (e.g., “Draft a status update about…”). Copilot will merge the situational prompt with this reusable guideline for more predictable output.
