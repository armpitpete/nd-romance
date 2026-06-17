# Web Data Carry-Forward Plan

## Purpose

The web builder should feel like one connected tool, not five separate forms.

At the moment, each page saves its own browser draft. That works, but it means the user may need to retype or copy the same project details across pages.

---

## Core decision

Use shared browser state first.

```text
localStorage
```

No database.
No login.
No API calls.

---

## Shared project state

Add one shared browser record for core project data.

Suggested key:

```text
ndrb-project-core-v1
```

This should hold the fields that are useful across pages.

---

## Fields to carry forward

## From Mini Design to later pages

Carry forward:

- working title
- romance type
- Person A name
- Person B name
- emotional promise
- main obstacle
- external pressure
- ND-readable truth
- ending requirement
- first scene seed
- first scene job
- first scene change

---

## From Structure Spine to Arc Map

Carry forward:

- working title
- primary pair
- emotional promise
- main obstacle
- external pressure
- ND-readable truth
- ending requirement
- opening contact
- deepening bond
- midpoint change
- pressure / fault line
- major test
- repair path
- ending proof

---

## From Arc Map to Scene Card

Carry forward:

- working title
- primary pair
- current relationship stage
- pressure stage
- major turn
- repair / recognition
- ending state

---

## From Scene Card to Draft Prompt

Carry forward:

- project title
- scene title
- point of view
- scene job
- start state
- scene conditions
- bond evidence
- misread / accuracy map
- beat map
- dialogue / subtext
- scene-end change
- hidden information / do not reveal yet

---

## User-facing behaviour

The app should not silently overwrite the user’s current page.

Preferred behaviour:

```text
Load from previous step
```

button on each later page.

This is safer than automatic import.

---

## Recommended first implementation

Start with one link in the chain:

```text
Mini Design → Structure Spine
```

Add a button to `structure.html`:

```text
Load from Mini Design
```

When clicked, it should copy available Mini Design fields into Structure Spine fields.

---

## Good enough for first implementation

- no database
- no API
- no change to existing exports
- add button only to `structure.html`
- copy title, pair names, emotional promise, main obstacle, external pressure, ND-readable truth, and ending requirement
- preserve manual editing after import

---

## Later implementation order

1. Mini Design → Structure Spine
2. Structure Spine → Arc Map
3. Arc Map → Scene Card
4. Scene Card → Draft Prompt

---

## Next issue

```text
Add Load from Mini Design button to Structure form
```
