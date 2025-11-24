# AGENTS.md - Everyday Prompts (Agent Guide)

> **Purpose**
> This file is the single source of truth for how coding agents should read, modify, generate, and review prompts in this repository.

---

## 0) Repo Orientation (Read Me First)

- **Prompts Folder Structure**: All prompts are organized by domain and sub-domain in the `prompts/` folder. Each prompt has its own markdown file with metadata, instructions, examples, and tips.
- **README Files**: Each folder contains a `README.md` that lists and describes the prompts within that category. Use these to navigate and understand the purpose of each prompt.
- **Metadata Standards**: Every prompt file includes frontmatter metadata such as `title`, `category`, `subcategory`, `description`, `llm_tools`, and `inputs`. This ensures consistency and helps with searching and filtering prompts.

---

## 1) Adding New Prompts

When adding a new prompt:

- **Verify Uniqueness**: Ensure a prompt does not already exist for the intended purpose.
- **Choose Correct Folder**: Place the new prompt in the appropriate domain/sub-domain folder.
- **Use Frontmatter**: Include all required metadata in the frontmatter.
- **Structure the Content**: Follow the established format: context, prompt, example, and tips.
- **Link in README**: Update the nearest `README.md` to include a link and description of the new prompt.

---

## 2) Modifying Existing Prompts

When modifying existing prompts:

- **Maintain Consistency**: Ensure changes align with the existing style and structure of the repository.
- **Update Metadata**: If the purpose or tools change, update the frontmatter accordingly.
- **Revise Examples**: Ensure examples reflect any changes made to the prompt instructions.

---

## 3) Reviewing Prompts

When reviewing prompts:

- **Check Clarity**: Ensure instructions are clear and unambiguous.
- **Test Functionality**: Run the prompt and verify it produces the expected results.
- **Validate Metadata**: Confirm that all metadata fields are accurate and complete.
- **Suggest Improvements**: Propose enhancements to improve usability or effectiveness.
- **Ensure Relevance**: Verify that the prompt remains relevant to current LLM capabilities and tools.
- **Cross-Reference**: Check for related prompts in other categories that may need updates or links.
