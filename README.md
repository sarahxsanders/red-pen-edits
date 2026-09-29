# Red pen edits

Do you ever miss getting a draft back from your English teacher, all marked up with red pen, and clear feedback on what needs fixing? Me too.

When I peer-edit with AI, I find myself frustrated with the output of my conversation. Feedback in the form of a giant word dump is hard to read. So I created a skill that gives me red pen edits for my own writing :)

It makes edits for clarity, structure, voice, tense, grammar, technical precision, and concision while preserving your intent and voice.

Its editing principles are informed by William Zinsser's *On Writing Well*: find the essential point, cut clutter, create unity, prefer precise words and verbs, protect the writer's voice, and treat rewriting as part of writing.

## Compatibility

The canonical skill lives at [`skills/red-pen-writing-review`](skills/red-pen-writing-review).

- **Claude Code:** `.claude/skills/red-pen-writing-review` points to the canonical skill.
- **Codex:** `.agents/skills/red-pen-writing-review` points to the same skill.
- **ChatGPT desktop:** the canonical folder is ready to add as a standalone skill and includes OpenAI display metadata in `agents/openai.yaml`.

Both platforms use the open Agent Skills format, so the core `SKILL.md` is shared instead of maintained as two drifting copies.

## Install for personal use

Clone this repository, then link the canonical skill into the platform you use.

### Claude Code

```sh
mkdir -p ~/.claude/skills
ln -s "$(pwd)/skills/red-pen-writing-review" ~/.claude/skills/red-pen-writing-review
```

Invoke it with `/red-pen-writing-review`, or ask Claude to review your draft.

### Codex

```sh
mkdir -p ~/.agents/skills
ln -s "$(pwd)/skills/red-pen-writing-review" ~/.agents/skills/red-pen-writing-review
```

Mention `$red-pen-writing-review` to invoke it directly.

### ChatGPT desktop

Add the `skills/red-pen-writing-review` folder through the Skills area in ChatGPT desktop. You can then select it explicitly, or let ChatGPT invoke it when your request matches its description.

## What it produces

- Concise self-review feedback
- A clean revised draft
- A standalone red-pen HTML manuscript with visible deletions, insertions, underlines, carets, and only necessary margin notes

## Scope

This skill is deliberately limited to reviewing and revising the user's own prose.
