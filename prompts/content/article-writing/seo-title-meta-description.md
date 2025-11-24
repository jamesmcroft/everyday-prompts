---
title: SEO Title & Meta Description
category: content
subcategory: article-writing
description: Generate search-friendly titles and 160-character meta descriptions tailored to your audience and key themes.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Target audience
  - Content format
  - High-level topics or content body
tags:
  - seo
  - metadata
  - titles
  - search-optimization
---

# SEO Title & Meta Description

Write or refine search-focused page metadata either before or after you draft an article. Use the "before" variation for ideation and the "after" variation once the copy exists so keywords reflect the final content.

## Prompt (Before Writing)

```text
Based on a [article|blog post|guide] for <TARGET AUDIENCE>, write an informative, search engine optimized title and description.

The description should summarize the topics in a concise and engaging manner, less than or equal to 160 characters.

It should represent the following high-level topics:

- <List out any specific resources or topics to cover>
```

### Example

```text
Based on a blog post for small business owners, write an informative, search engine optimized title and description.

The description should summarize the topics in a concise and engaging manner, less than or equal to 160 characters.

It should represent the following high-level topics:

- Understanding your target audience
- Content, social media, and email marketing strategies
- Measuring marketing success
```

## Prompt (After Writing)

```text
Based on the following content, write an informative, search engine optimized title and description.

The description should summarize the content in a concise and engaging manner, less than or equal to 160 characters.

Content:
<Paste the content you have written>
```

> [!TIP]
> In Edge's Copilot, @mention the page tab so the model automatically references the page you are editing without pasting the entire article.
