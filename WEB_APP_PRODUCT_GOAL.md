# Web App Product Goal

## Core goal

The web app exists so a user can fill in guided romance forms and generate a romance story.

The app should reduce overwhelm by turning story creation into a controlled step-by-step process.

---

## Plain goal statement

```text
Fill in the forms.
Generate the romance plan.
Generate the romance story draft.
Revise from the same structure.
```

---

## Product stages

## Stage 1 — Planning generator

Current stage.

The app helps the user fill in:

1. Mini Design Sheet
2. Structure Spine
3. Arc Map
4. Scene Card

Output:

```text
Markdown planning files
```

This stage does not need AI.

---

## Stage 2 — Scene draft generator

Next major stage after the planning forms work.

The app should use the completed Scene Card to generate a first prose scene draft.

Output:

```text
Chapter or scene draft in Markdown
```

This may need an AI step later, but not before the manual planning flow is stable.

---

## Stage 3 — Story generator

Later stage.

The app should use the full project inputs to generate a romance story draft.

Inputs:

- Mini Design Sheet
- Structure Spine
- Arc Map
- Scene Cards
- style rules
- ND-readable writing rules

Output:

```text
A readable romance story draft
```

---

## Important rule

Do not jump straight to full story generation.

The story draft will only be useful if the app first captures:

- the two people
- why these two
- the real obstacle
- the external pressure
- the relationship arc
- the scene jobs
- the ND-readable truth layer
- the ending requirement

---

## Current build direction

Keep building the form flow first.

Recommended next screen:

```text
Structure Spine form
```

Reason:

The Mini Design Sheet captures the premise.
The Structure Spine turns that premise into a story path.
Without the Structure Spine, the app can only generate an idea, not a story.

---

## Feature creep boundary

Do not add yet:

- accounts
- database
- payments
- social sharing
- collaboration
- full manuscript editor
- general AI chat

The first useful product is a guided story generator, not a platform.
