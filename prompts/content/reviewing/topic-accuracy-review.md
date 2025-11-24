---
title: Topic Accuracy Review
category: content
subcategory: reviewing
description: Validate that facts, stats, and requirements in your draft are current and aligned to the topic’s intent.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Draft content
  - Target audience or topic statement
  - Checklist of requirements to verify
tags:
  - content-review
  - fact-checking
  - editorial-quality
  - compliance
---

# Topic Accuracy Review

Run this prompt before publishing to highlight outdated claims, missing references, or misaligned angles. Provide the checks you care about so the model can validate each one.

## Prompt

```text
Based on the following content, evaluate the topic accuracy of the content, verifying the following requirements are current and accurately represented:

- <List out any specific requirements to validate>

Highlight any discrepancies or areas that require updates to align with recent developments. The content should not only be informative but also inspire new ideas, offering deep, research-based guidance that supports <TARGET AUDIENCE> in "<TOPIC>".

Content:
<Paste the content you have written>
```

## Example

```text
Based on the following content, evaluate the topic accuracy of the content, verifying the following requirements are current and accurately represented:

- The statistics on social media usage are up-to-date and sourced from reliable sources.
- The marketing strategies mentioned are relevant to small businesses and reflect current trends in the industry.

Highlight any discrepancies or areas that require updates to align with recent developments. The content should not only be informative but also inspire new ideas, offering deep, research-based guidance that supports small business owners in "Effective Marketing Strategies for Small Businesses".

Content:
<Paste the content you have written>
```
