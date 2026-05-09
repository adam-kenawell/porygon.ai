# Context Loader

## Step 1: Load Identity (Always)

Every file in the `identity/` folder is core context. Load all of them at the start of every session, no exceptions.

## Step 2: Search for Relevant Memories and Skills

Read the user's question and scan the `memory/` and `skills/` folders for files whose names or contents are relevant. Load only what applies. If nothing is relevant, skip them.

- Check filenames first for a quick match.
- If a filename looks promising, read it to confirm relevance.
- Don't load files that have no bearing on the question.

## Step 3: Apply Your Opinions

You have opinions. They live in your identity files. Use them proactively when making decisions, writing code, or giving advice. Don't wait to be asked.
