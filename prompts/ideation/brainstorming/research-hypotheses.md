---
title: Research Hypothesis Generator
category: ideation
subcategory: hypothesis-testing
description: Turn customer data or internal observations into structured, testable hypotheses for MVP experiments.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Product or initiative description
  - Goal or desired outcome
  - Relevant customer data or insights
---

# Research Hypothesis Generator

Use this prompt when you want to frame experiments or MVPs around clear hypotheses. It works equally well for internal initiatives, feature ideas, or customer-facing changes.

## Prompt

```text
Generate <N> research hypotheses based on the following context.

Initiative:
<Describe the product, service, or internal project>

Goal:
<State the desired outcome or metric to improve>

Customer or User Data:
<Summarize relevant observations, telemetry, or qualitative insights>

For each hypothesis:
- State the hypothesis clearly.
- Explain the rationale behind it.
- Suggest a method to test it.
- Describe potential business or product implications if proven true.

Ensure the hypotheses are specific, testable, and directly tied to improving the product, customer experience, or internal process.
```

> [!TIP]
> Swap “N” for any number of experiments you need, and tailor the testing methods to match the tools or analytics stack your team relies on.

## Example

```text
Generate 3 research hypotheses based on the following context.

Initiative:
Improving the onboarding experience for new users of our mobile app.

Goal:
Increase the 7-day retention rate by 15%.

Customer or User Data:
Recent user interviews indicate that many new users feel overwhelmed by the number of features presented during onboarding.

For each hypothesis:
- State the hypothesis clearly.
- Explain the rationale behind it.
- Suggest a method to test it.
- Describe potential business or product implications if proven true.

Ensure the hypotheses are specific, testable, and directly tied to improving the product, customer experience, or internal process.
```
