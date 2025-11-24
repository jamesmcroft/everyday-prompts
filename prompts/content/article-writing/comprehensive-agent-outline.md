---
title: Agentic Editorial Blueprint
category: content
subcategory: article-writing
description: One-shot prompt for reasoning models to plan titles, metadata, challenges, benefits, sections, and conclusions in a single pass.
llm_tools:
  - ChatGPT (GPT-5 / Agent Mode)
  - Microsoft Copilot
inputs:
  - Content format (research paper, article, blog post, book chapter)
  - Target audience
  - Topic
  - Number of sections
  - Specific subtopics or resources to cover
tags:
  - editorial-planning
  - seo
  - content-blueprint
  - agentic-workflows
---

# Agentic Editorial Blueprint

Reasoning-enabled models can coordinate complex responses without stitching together multiple prompts. Use this blueprint when you want a single instruction that delivers the SEO title, meta description, intro, challenge/benefit bullets, detailed sections, and a conclusion in one go.

## Prompt

```text
We are writing a [research paper|article|blog post|book chapter] for <TARGET AUDIENCE> on <TOPIC>.

Provide an outline with <N> sections including:

- An informative, search engine optimized title that represents the high-level topics.
- A meta description that summarizes the content in a concise and engaging manner, which is search engine optimized. It should be less than or equal to 156 characters.
- An introduction that clearly articulates the challenge or problem that <TARGET AUDIENCE> face and clearly states how the [research paper|article|blog post|book chapter] addresses that problem for them.
- 2-3 key business challenges that <TARGET AUDIENCE> face with <TOPIC> as detailed bullet points.
- 2-3 insightful benefits that <TARGET AUDIENCE> will gain from reading the [research paper|article|blog post|book chapter] on <TOPIC> as detailed bullet points.
- Sections which dive into the following areas, making a case to readers on how they should implement the given initiative. Make the subject easy to understand and act upon. Focus on actionable advice using words such as choose, use, and avoid. Keep it concise.
  - <List out any specific resources or topics to cover>
- A short paragraph to conclude the [research paper|article|blog post|book chapter] that summarizes the main points and provides a recommendation for future research or action.
```

## Example

```text
We are writing a blog post for enterprise product leaders on Continuous Discovery.

Provide an outline with 6 sections including:

- An informative, search engine optimized title that represents the high-level topics.
- A meta description that summarizes the content in a concise and engaging manner, which is search engine optimized. It should be less than or equal to 156 characters.
- An introduction that clearly articulates the challenge or problem that enterprise product leaders face and clearly states how the blog post addresses that problem for them.
- 2-3 key business challenges that enterprise product leaders face with Continuous Discovery as detailed bullet points.
- 2-3 insightful benefits that enterprise product leaders will gain from reading the blog post on Continuous Discovery as detailed bullet points.
- Sections which dive into the following areas, making a case to readers on how they should implement the given initiative. Make the subject easy to understand and act upon. Focus on actionable advice using words such as choose, use, and avoid. Keep it concise.
  - Customer interview cadences
  - Opportunity solution trees
  - Exec reporting frameworks
- A short paragraph to conclude the blog post that summarizes the main points and provides a recommendation for future research or action.
```

> [!TIP]
> If you are using ChatGPT’s GPT-5 or Agent Mode, paste this prompt as-is and let the model orchestrate the multi-part response without extra follow-up prompts. Otherwise, I recommend leveraging [the individual article writing prompts](./README.md) for more control over each section of the article.
