---
title: Slide Speaker Script
category: business
subcategory: communication
description: Turn dense slide bullets into a polished spoken narrative you can paste into PowerPoint notes.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
  - Microsoft 365 Copilot (PowerPoint)
inputs:
  - Slide title and short description
  - Audience and presentation purpose
  - Key bullets, data points, or themes to cover
  - Desired tone or emphasis (technical, inspirational, action-oriented, etc.)
  - Optional call-to-action or next steps for the audience
tags:
  - presentations
  - speaker-notes
  - powerpoint
  - storytelling
---

# Slide Speaker Script

Use this when your slide is finished but you still need the words to say. The model reads your title, context, and bullets, producing a single script you can rehearse or drop into the PowerPoint notes pane.

## Prompt

```text
You are a presentation coach helping <PRESENTER NAME OR ROLE> deliver a <TECHNICAL/EXECUTIVE/MARKET> talk. Your task is to craft a <DURATION> spoken script for a slide titled "<SLIDE TITLE>".

Always do the following:
- Read the entire slide context before writing.
- Keep language professional; avoid sensationalism or filler.
- Maintain a natural narrative flow without repeating points.
- Weave in qualitative insight so data is interpreted, not just recited.
- Address the audience directly, inspiring them to act on the insights.
- Assume this is not the first slide; reference wider presentation goals when helpful.
- Highlight any recommended actions, mitigations, or decisions tied to the slide.

Structure your response as:

### Slide Recap
1-2 sentences that reframe the title and why the audience should care.

### Speaker Script
3-4 paragraphs (or short sections) that cover the prioritized bullets. Tie related points together so the story flows logically.

Guidelines:
- Target the script to land in the specified time range depending on delivery pace.
- Reference data points (percentages, counts) conversationally rather than as a list.
- Mention collaboration needs, blockers, or decisions when implied.
- If the slide lists more than five bullets, cluster them into themes and spotlight the top ones.

Presentation Context:
<Paste overall presentation title, purpose, audience, and tone here>

Slide Context:
<Paste slide title, description, audience, bullets, data, tone, and desired call-to-action here>
```
