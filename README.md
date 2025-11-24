# Everyday Prompts

[![GitHub Issues][badge_issues]][link_issues]
[![GitHub Stars][badge_repo_stars]][link_repo]
[![Repo License][badge_license]][link_repo]

A library of copy-ready prompts for ChatGPT, Copilot, and similar tools. Every prompt lives in its own file, grouped into categorized folders so you can jump straight to what you need.

## Find a Prompt

All prompts live under [`prompts/`](prompts/README.md). The folder categories are intentionally opinionated to keep things organized:

| Domain                 | Folder                            | Highlights                                                    |
| ---------------------- | --------------------------------- | ------------------------------------------------------------- |
| Content - Writing      | `prompts/content/`                | Outlining, SEO metadata, feature images, conclusions          |
| Content - Reviewing    | `prompts/content/reviewing/`      | Language quality checks, topic accuracy, readability feedback |
| Social Media           | `prompts/social/`                 | Conversation-starting posts and image prompts                 |
| Coding                 | `prompts/coding/`                 | Release-note system prompt ready for changelog inputs         |
| Knowledge Retrieval    | `prompts/knowledge/`              | Context-grounded answering for RAG setups                     |
| Business Communication | `prompts/business/communication/` | Outlook Copilot drafting rules and stakeholder messaging      |
| Career Development     | `prompts/career/development/`     | Performance reviews, growth plans, and professional coaching  |

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
