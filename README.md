# Everyday Prompts

[![GitHub Issues][badge_issues]][link_issues]
[![GitHub Stars][badge_repo_stars]][link_repo]
[![Repo License][badge_license]][link_repo]

A library of copy-ready prompts for ChatGPT, Copilot, and similar tools. Every prompt lives in its own file, grouped into categorized folders so you can jump straight to what you need.

## Find a Prompt

All prompts live under [`prompts/`](prompts/README.md). The folder categories are intentionally opinionated to keep things organized:

### Coding

| Category                                                            | Highlights                                   |
| ------------------------------------------------------------------- | -------------------------------------------- |
| [`Release Management`](prompts/coding/release-management/README.md) | Release notes and changelog prep             |
| [`Issue Management`](prompts/coding/issue-management/README.md)     | GitHub bug reports and issue triage          |
| [`Coding Agents`](prompts/coding/coding-agents/README.md)           | Spec-driven work items for autonomous agents |

### Business

| Category                                                    | Highlights                                         |
| ----------------------------------------------------------- | -------------------------------------------------- |
| [`Communication`](prompts/business/communication/README.md) | Email drafting, stakeholder messaging helpers      |
| [`Meetings`](prompts/business/meetings/README.md)           | Structured recaps of recorded/transcribed sessions |
| [`Goal Setting`](prompts/business/goal-setting/README.md)   | Structured OKR drafting and target tracking        |

### Career

| Category                                              | Highlights                                               |
| ----------------------------------------------------- | -------------------------------------------------------- |
| [`Development`](prompts/career/development/README.md) | Performance reviews, growth plans, professional coaching |

### Journaling

| Category                                                | Highlights                                                           |
| ------------------------------------------------------- | -------------------------------------------------------------------- |
| [`Reflection`](prompts/journaling/reflection/README.md) | Weekly and monthly impact journals for business and career alignment |

### Content Writing

| Category                                                       | Highlights                                                    |
| -------------------------------------------------------------- | ------------------------------------------------------------- |
| [`Article Writing`](prompts/content/article-writing/README.md) | Outlining, SEO metadata, feature images, conclusions          |
| [`Reviewing`](prompts/content/reviewing/README.md)             | Language quality checks, topic accuracy, readability feedback |

### Ideation

| Category                                                    | Highlights                                               |
| ----------------------------------------------------------- | -------------------------------------------------------- |
| [`Brainstorming`](prompts/ideation/brainstorming/README.md) | Idea generation, hypothesis framing, and experimentation |

### Social Media

| Category                                                    | Highlights                                                        |
| ----------------------------------------------------------- | ----------------------------------------------------------------- |
| [`Media Creation`](prompts/social/media-creation/README.md) | Conversation-starting posts on LinkedIn, and social image prompts |

### Knowledge

| Category                                                                       | Highlights                                                                |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| [`Research Orchestration`](prompts/knowledge/research-orchestration/README.md) | Multi-agent research loops with observations, gap analysis, and synthesis |
| [`Retrieval & Q&A`](prompts/knowledge/retrieval-qa/README.md)                  | Context-grounded answering for RAG setups                                 |

## How to Use

1. Browse to a category folder and open its `README.md` for a quick description of every prompt inside.
2. Open the prompt file you need - each one includes metadata, when-to-use guidance, the exact prompt, and an example.
3. Copy the prompt into your LLM tool and replace `[ ]` or `< >` placeholders with your information.
4. Iterate! These prompts are meant to be tweaked and combined to match your workflow.

> [!TIP]
> Naming and metadata stay consistent across folders, so you can search for tags such as `subcategory: article-writing` in your editor to find related prompts fast.

## Recommended Tools

- [**ChatGPT**](https://chat.openai.com/): Handles long-form prompts, supports text + image generation, and lets you package favorite prompts into custom GPTs.
- [**Microsoft Copilot**](https://copilot.microsoft.com/): Great for contextual prompts via the Edge sidebar. Switch to the Notebook view for longer context windows or use Copilot Pro to build Copilot GPTs. Learn more about [Copilot in Microsoft Edge](https://learn.microsoft.com/en-us/copilot/edge).
- [**M365 Copilot**](https://www.microsoft.com/en-us/microsoft-365/copilot): Integrates AI directly into Microsoft 365 apps like Word, Excel, and Outlook for context-aware assistance. Great for business workflows.

## Tips

### Microsoft Copilot

- **Using the current web page as context**: In Edge's Copilot feature, @mention the tab you want to include as context so prompts like SEO metadata or contextual reviews automatically reference the page.

## Supporting

If you find this repository helpful, consider supporting it by starring the repository or sharing it with others.

Contributions are also welcome! If you have prompts to add or have improvements to existing prompts, feel free to propose changes.

## Author

👤 James Croft

[![Website][badge_blog]][link_blog]
[![LinkedIn][badge_linkedin]][link_linkedin]

## License

The repo is made available under the terms and conditions of the [MIT license](LICENSE).

[badge_blog]: https://img.shields.io/badge/blog-jamesmcroft.co.uk-blue?style=for-the-badge
[badge_linkedin]: https://img.shields.io/badge/LinkedIn-jmcroft-blue?style=for-the-badge&logo=linkedin
[badge_license]: https://img.shields.io/github/license/jamesmcroft/everyday-prompts?style=for-the-badge
[badge_issues]: https://img.shields.io/github/issues/jamesmcroft/everyday-prompts?style=for-the-badge
[badge_repo_stars]: https://img.shields.io/github/stars/jamesmcroft/everyday-prompts?logo=github&style=for-the-badge
[link_blog]: https://www.jamescroft.co.uk/
[link_linkedin]: https://www.linkedin.com/in/jmcroft
[link_issues]: https://github.com/jamesmcroft/everyday-prompts/issues
[link_repo]: https://github.com/jamesmcroft/everyday-prompts
