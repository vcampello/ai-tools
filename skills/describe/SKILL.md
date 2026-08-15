---
name: describe
description: Use when the user asks to describe, summarize, or explain something. Produces a short, copy-pasteable description.
---

# describe

Generate a description of whatever the user wants described, based on their request and the surrounding context.

## How it works

1. Identify the target of the description (a change, a diff, a feature, a concept, a process, etc.).
2. Gather the relevant context to describe it accurately.
3. Infer the intent or purpose where applicable, not just surface details.
4. Match the user's writing and communication style (vocabulary, tone, formatting) where it is acceptable and clear, staying terse even when adopting their style; otherwise default to plain, terse language.
5. Produce a concise description, copy-pasteable into the intended destination (GitHub, a doc, a message, etc.).

## Output

- A one-line summary (title).
- A short description covering what and why.
- A bullet list of key points when the target is multi-part.
- No em dashes.
- Prefer bullets in the form `- **bold wording:** content`.
