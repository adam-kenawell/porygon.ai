# porygon.ai

A template for building a personalized AI coding assistant using GitHub Copilot's [custom instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions).

## What Is This?

This project provides a structured set of `.instructions.md` files that shape how GitHub Copilot behaves in your workspace. By filling in these files, you give Copilot context about who you are, how you think, and what you value — resulting in responses that feel tailored to you.

## Project Structure

```text
identity/          # Who the AI is and who it's working with
  owner.instructions.md          # Info about you (name, role, preferences)
  personality.instructions.md    # The AI's personality and tone
  thought-process.instructions.md # How the AI should approach problems

memory/            # Persistent context the AI should remember
  example.instructions.md       # Template — add your own memory files here

opinions/          # Coding opinions and principles the AI should follow
  concision-over-verbosity.md
  depth-over-breadth.instructions.md
  mental-audit.instructions.md
  test-driven-development.instructions.md

skills/            # Domain-specific knowledge or capabilities
  example.instructions.md       # Template — add your own skill files here
```

## Getting Started

1. **Fork or clone** this repository.
2. **Fill in the instruction files.** Each `.instructions.md` file is a blank canvas. Write plain-text or Markdown guidance that Copilot should follow. For example:
   - `identity/owner.instructions.md` — _"My name is Jane. I'm a backend engineer working primarily in Go and Python."_
   - `identity/personality.instructions.md` — _"Be direct. Avoid filler phrases. Use dry humor sparingly."_
   - `opinions/test-driven-development.instructions.md` — _"Always suggest writing tests before implementation."_
3. **Add or remove files** to match your needs. The folder structure is a suggestion, not a requirement.
4. **Open your project in VS Code** with GitHub Copilot enabled. Copilot will automatically pick up any `.instructions.md` files in the workspace.

## Adding New Instructions

Create any `.instructions.md` file anywhere in the repo. Copilot scans the entire workspace for them. Use the folder structure to stay organized:

- **identity/** — Who you are and how the AI should behave.
- **memory/** — Things the AI should always remember (project context, decisions, etc.).
- **opinions/** — Coding style, principles, and preferences.
- **skills/** — Specialized knowledge (frameworks, APIs, domain logic).

## Tips

- Keep each file focused on a single topic.
- Write instructions as if you're briefing a new team member.
- Be specific — _"Use `snake_case` for Python variables"_ beats _"Follow good naming conventions."_
- Revisit and update files as your preferences evolve.

## License

Use however you'd like. This is a starting point — make it yours.
