# First Scene Draft Generator Plan

## Purpose

The first draft-generator step should turn a completed Scene Card into a usable scene-drafting brief.

It should help the user move from planning to prose without jumping straight into a full automated writing platform.

---

## Core decision

Version 0 should generate:

```text
A clean scene draft brief and AI prompt
```

It should not directly call an AI API yet.

---

## Why this is the right next step

The web app now has the core planning path:

```text
Mini Design
Structure Spine
Arc Map
Scene Card
```

The Scene Card is the correct first input for draft generation because it contains:

- scene identity
- scene job
- point of view
- start states
- conditions
- bond evidence
- misread / accuracy map
- beat map
- dialogue / subtext
- scene-end change

That is enough to produce a focused first scene draft.

---

## v0 output

The draft generator should produce a Markdown file called:

```text
scene_draft_prompt.md
```

It should include:

1. scene summary
2. writing instructions
3. style rules
4. ND-readable rules
5. scene-card facts
6. draft prompt
7. space for generated prose

---

## v0 page

Recommended page:

```text
web/draft.html
```

Page purpose:

```text
Paste or fill Scene Card details.
Generate a clean prompt for drafting the scene.
Copy or download the prompt.
```

---

## v0 fields

Use these fields first:

- project title
- scene title
- point of view
- scene job
- start state
- scene conditions
- bond evidence
- misread / accuracy map
- beat map
- scene-end change
- tone / style note
- draft length target

---

## v0 prompt rules

The generated prompt should tell the AI or writer:

- write the scene in prose
- stay in the chosen point of view
- follow the beat map
- show care through behaviour, not explanation
- keep the emotional meaning clear
- avoid vague social fog
- avoid melodrama unless requested
- do not over-explain neurodivergence
- use plain readable language
- end with the required scene-end change

---

## Not in v0

Do not add yet:

- OpenAI API call
- login
- database
- payment
- cloud storage
- manuscript editor
- full story generation
- automatic GitHub save
- Google Drive sync

---

## v1 later

After v0 works, the next stage can be:

```text
Generate prose directly using an API
```

But only after:

- the prompt format is tested
- the scene outputs are useful
- the user knows what should change in the generated prose

---

## Product rule

The app should generate story drafts from structure, not from vague prompts.

Correct direction:

```text
forms → structured plan → scene card → scene draft prompt → prose draft
```

Wrong direction:

```text
type one vague idea → generate a whole romance
```

---

## Next implementation issue

Title:

```text
Build static Scene Draft Prompt form
```

Good enough:

- add `web/draft.html`
- use Scene Card fields
- generate a copyable draft prompt
- include download `.md`
- no API yet
