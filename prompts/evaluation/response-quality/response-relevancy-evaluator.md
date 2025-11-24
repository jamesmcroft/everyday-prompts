---
title: Response Relevancy Evaluator
category: evaluation
subcategory: response-quality
description: Determine whether an AI response directly addresses the user query using the provided context.
llm_tools:
  - ChatGPT
  - Claude
  - Gemini
inputs:
  - User query or request
  - Context supplied to the answering model (documents, notes, snippets)
  - Model response to evaluate
---

# Response Relevancy Evaluator

Use this evaluator prompt to quickly judge if a generated answer actually addresses the question while staying grounded in the supplied context. It works well for retrieval-augmented generation (RAG) checks, leaderboard evaluations, or lightweight QA pipelines where you need reasoning alongside the verdict.

## Prompt

```text
We have been working on the following query:

{query}

We provided the following context:

{context}

And we have received the following response:

{response}

To ensure the response provided is relevant to the query, please answer the following question, including your reasoning:

- Is the response provided relevant to the query provided? This includes the execution of the query, the provision of all requested information, and its relevance to the query.
```

## Example

```text
We have been working on the following query:

<QUERY>
Summarize the three most important features mentioned in our 2025 premium plan launch notes.
</QUERY>

We provided the following context:

<CONTEXT>
Excerpt: The 2025 premium plan launch introduced (1) unlimited work item automations, (2) hourly workspace backups retained for 30 days, and (3) security posture reports with automated CVE lookups.
</CONTEXT>

And we have received the following response:

<RESPONSE>
The premium plan focuses on automation, faster CI builds, and bundled design templates that ship later this year.
</RESPONSE>

To ensure the response provided is relevant to the query, please answer the following question, including your reasoning:

- Is the response provided relevant to the query provided? This includes the execution of the query, the provision of all requested information, and its relevance to the query.
```

## Tips

- Pair this evaluator with automated scoring by checking for positive or negative signals (e.g., "Yes" vs. "No") in the reasoning output.
- Capture both the verdict and explanation so you can audit disagreements and refine upstream prompts.
- Feed the evaluator exactly what the answering agent saw to avoid penalizing answers for missing context.
