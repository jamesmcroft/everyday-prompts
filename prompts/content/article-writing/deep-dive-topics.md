---
title: Deep Dive Topic Generator
category: content
subcategory: article-writing
description: Turn existing context or outlines into drill-down article ideas for deeper follow-up pieces.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Source context (notes, article, outline, or headings)
---

# Deep Dive Topic Generator

Use this prompt after publishing an article or outlining a series to uncover rich follow-up topics. It first surfaces three overall deep-dive ideas, then maps specific drill-down angles to each heading in your context.

## Prompt

```text
Based on the following context, provide 3 potential deep dive, drill down content topics that would make for great articles.

---

For each heading, provide a potential deep dive, drill down content topic that would make for a great article.

Context:
<Paste article draft, outline headings, or research notes>
```

## Example

```text
Context:
# Modern Customer Support Playbooks
## Heading: Building a Proactive Support Culture
## Heading: Leveraging AI Assistants in Support
## Heading: Measuring Support Quality Beyond CSAT
```

The model will return three net-new deep dive article titles plus one tailored drill-down topic per heading so you can keep expanding the series with intent.
