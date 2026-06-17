# Web Interface Prototype Plan

## Purpose

Create a minimal web interface for the ND Romance pack.

The interface should make the existing workflow easier to use. It should not replace the Markdown pack.

---

## Core decision

Build a small static web prototype first.

Do not build a full app yet.

---

## First prototype name

Working name:

```text
ND Romance Builder
```

---

## What the prototype should do

The first version should let a user:

1. move through the workflow step by step
2. fill in simple form fields
3. see a short example beside the form
4. generate Markdown output
5. copy or download the Markdown file

---

## What it should not do yet

Do not add:

- user accounts
- login
- database
- cloud saving
- payments
- AI writing assistant
- GitHub sync
- Google Drive sync
- collaboration tools
- full manuscript editor

Those are later possibilities only.

---

## First workflow screens

## 1. Home

Purpose:

- explain what the tool does
- offer one button: Start a Romance Project

Content:

```text
Build a clear romance project one step at a time.
Start with the Mini Design Sheet.
Export Markdown when done.
```

---

## 2. Mini Design Sheet

Fields:

- working title
- romance type
- Person A name
- Person A current life pattern
- Person A want
- Person A fear in closeness
- Person B name
- Person B current life pattern
- Person B want
- Person B fear in closeness
- why these two
- emotional promise
- main obstacle
- external pressure
- ND-readable truth
- ending requirement
- first scene seed

Output:

```text
mini_design.md
```

---

## 3. Structure Spine

Fields:

- emotional promise
- main obstacle
- external pressure
- ND-readable truth
- ending requirement
- opening contact
- deepening bond
- midpoint change
- pressure and fault line
- major test
- repair path
- ending proof
- chapter spine rows

Output:

```text
structure_spine.md
```

---

## 4. Arc Map

Fields:

- starting state
- first change
- pattern formation
- trust opening
- pressure stage
- major turn
- repair / recognition
- ending state
- chapter arc rows

Output:

```text
arc_map.md
```

---

## 5. Scene Card

Fields:

- scene title
- chapter / position
- point of view
- location
- relationship stage at scene start
- scene job
- start state for Person A
- start state for Person B
- scene conditions
- bond evidence
- misread / accuracy map
- beat map
- scene-end change
- keep / revise / cut decision

Output:

```text
scene_card.md
```

---

## 6. Export

The export screen should allow:

- copy Markdown
- download `.md`
- clear form
- start next step

No account required.

---

## Data model

No database in v0.1.

Use browser state only:

```text
localStorage
```

This allows the browser to remember draft form data without needing a backend.

---

## Hosting

Likely first host:

```text
GitHub Pages
```

Reason:

- repo already exists
- static app is enough
- no server needed
- easy to test publicly

---

## Technology options

### Simplest

```text
plain HTML + CSS + JavaScript
```

Best if the first version should be very small.

### Slightly better later

```text
Vite
```

Best if the interface grows into multiple components.

### Not needed yet

```text
Next.js
database
server backend
login system
```

Too much for the first prototype.

---

## Design rules

The interface should be:

- one question at a time where possible
- large readable text
- low visual clutter
- clear save/export buttons
- no dashboard overload
- no long theory sections in the form screens

---

## First build issue after this plan

Recommended next issue:

```text
Build static Mini Design Sheet form
```

Good enough:

- one HTML page
- Mini Design fields
- generate Markdown preview
- copy Markdown button
- no styling polish beyond readability

---

## Final decision

Proceed with a thin static interface.

Do not build a full online platform yet.
