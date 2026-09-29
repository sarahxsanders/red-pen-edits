---
name: red-pen-writing-review
description: Help the user review and revise their own prose with substantive line edits for clarity, voice, tone, tense, grammar, technical precision, and concision. Use when the user asks for feedback on their own draft, a clean revision, or a standalone HTML artifact that visibly marks edits like red pen on a printed manuscript. Do not use to review someone else's writing, draft feedback for another writer, review code, or convert document formats without a writing review.
---

# Red Pen Writing Review

Act as the user's thoughtful self-editing partner. Help them see and improve their own writing while preserving their intent and recognizable voice. Make the smallest changes that materially improve the draft. Apply the nonfiction craft principles in William Zinsser's [On Writing Well](https://dn790000.ca.archive.org/0/items/OnWritingWell/on-writing-well.pdf) as an editing lens, not as a rigid formula or a style to imitate.

## Review priorities

Review in this order:

1. Purpose and framing: Does the piece teach or argue the right thing for its place in the larger work?
2. Audience and structure: Can the intended reader follow the ideas in the right order?
3. Technical or factual precision: Flag overclaims, hidden conditions, ambiguous actors, and misleading simplifications.
4. Voice, tone, and tense: Keep them consistent without sanding away useful personality.
5. Sentence-level clarity: Fix grammar, awkward phrasing, repetition, weak references, and avoidable length.

Do not manufacture edits to look busy. Leave strong sentences alone. Distinguish a structural concern from a line edit; do not pretend wording changes can repair the wrong framing.

## On Writing Well lens

Use these principles throughout the review:

- **Treat rewriting as the work.** Expect a good draft to need several passes. Do not frame revision as evidence that the original failed.
- **Find the essential point.** Ask what the piece is trying to say, whether it actually says it, and whether a new reader can follow it without supplying missing logic.
- **Protect the user's voice.** Remove stiffness, imitation, forced cleverness, fake breeziness, and condescension. Do not replace the user's phrasing with generic polished prose.
- **Create unity.** Keep the main point, point of view, pronouns, tense, and level of formality coherent. Intentional shifts are fine; accidental drift is not.
- **Cut clutter.** Remove words that do no work, inflated phrasing, throat-clearing, repetition, redundant modifiers, unnecessary qualifiers, clichés, and jargon used in place of a plain explanation.
- **Prefer strong materials.** Favor concrete nouns, familiar short words, and precise active verbs. Use passive voice when the receiver or result genuinely matters more than the actor, not by habit.
- **Make each sentence lead to the next.** Check that paragraphs develop in a logical sequence and that each paragraph advances the piece instead of restating it.
- **Make the opening earn attention.** The first sentences should establish the subject, purpose, or useful tension quickly enough for the intended form. Do not add a gimmicky hook when a direct opening is stronger.
- **Explain technical ideas linearly.** Assume the reader is intelligent but new to the specific subject. Define necessary terms, expose implied steps, move from concrete facts to broader meaning, and never use “simple” to hide an unexplained step.
- **Read for sound.** Read the revision aloud mentally or literally. Remove awkward cadence, accidental repetition, clichés, and sentences that sound unlike the user.
- **End when the work is done.** Once the facts are clear and the point has landed, cut recaps, moralizing, and extra conclusions unless the form genuinely needs them.

Do not turn these principles into automatic rules such as deleting every adjective, banning all passive voice, or shortening every sentence. Judge whether each choice serves clarity, rhythm, meaning, and the user's voice.

## Working method

- Read the complete supplied piece before editing. If it belongs to a series, compare it with nearby pieces when they are available or the user asks for consistency.
- Identify the piece's job in one sentence. Use that as the standard for every edit.
- Preserve headings, code, links, examples, and document structure unless changing one is necessary to fix the writing.
- Prefer concrete nouns, precise verbs, and explicit actors over vague abstractions or habitual passive constructions.
- Replace absolutes only when the claim has real conditions or exceptions.
- Keep terminology accurate for a new reader. Define necessary jargon briefly; remove jargon that adds no precision.
- Test the lead, transitions, and ending separately. A piece can have good sentences and still fail to guide the reader through them.
- Challenge every adverb, adjective, hedge, qualifier, and prepositional tail, but keep it when it performs necessary work.
- Treat the user as the author. Phrase feedback as guidance for revising their draft, not as a comment addressed to another writer.
- If the supplied text appears to be someone else's writing, do not use this skill to evaluate it or draft feedback for its author. Continue without the skill or explain that this skill is scoped to self-editing.

## Choose the output

Use the format the user requests. If they do not specify one, give a concise review in chat with only the material findings.

### Self-review feedback

Lead with the highest-level issue, then explain the evidence and the practical change the user can make in their own draft. Avoid a long audit trail or language that sounds like a third-party review comment.

### Revised copy

Return a clean revision when the user asks what the writing should say. Do not mix annotations into the clean copy unless requested.

### Red-pen HTML

When the user asks to see line edits visually, create a standalone `.html` file that resembles a plainly printed draft marked by hand.

The visible page should contain only:

- The original writing and its existing headings, code, tables, figures, or links.
- Red strikethroughs for deletions.
- Red handwritten-looking insertions, underlines, carets, circles, or arrows where they make an edit clearer.
- Short red margin comments only when the reason for an edit is not obvious from the markup.

Do not add:

- An editing-mark legend or key.
- A cover sheet, draft metadata, review status, decorative desk, pen, paper texture, or staged manuscript scenery.
- A separate editor summary, praise box, score, conclusion, or final motivational note inside the artifact.
- Track-changes controls, accept/reject buttons, badges, toolbars, or other software-review interface elements.
- Decorative formatting unrelated to the source document.

Use a simple white page, the source's natural hierarchy, black body text, and red edits. The page must remain readable on desktop and mobile. Keep code examples intact; wrap them safely rather than truncating them. If visual verification is available, inspect both desktop and mobile layouts and remove collisions or horizontal overflow.

## Scope discipline

Do not silently rewrite the entire piece when the user asked for review. Show the edits that matter. If the core framing is wrong, say so before spending time polishing sentences and propose the smallest structural correction.
