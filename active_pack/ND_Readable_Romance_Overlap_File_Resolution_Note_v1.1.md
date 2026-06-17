---
title: ND Readable Romance Overlap File Resolution Note
version: 1.1
status: locked-control
project: Writing
category: romance-control
purpose: >
  A corrected overlap-resolution note recording what overlap was real, what was
  not present in the reviewed pack, and what archive action is actually needed
  now.
use_for:
  - overlap cleanup
  - archive decisions
  - anti-drift audit
---

# ND Readable Romance Overlap File Resolution Note v1.1

## Core finding

There was **one active overlap problem** in the reviewed pack state:

- `ND_Romance_Revision_Workflow_v1.0.md`

This file sat outside the canonical `ND_Readable_Romance_*` naming line while still doing live work.

---

## Important correction

An earlier overlap note discussed two `ND_Romance_*` files.

In the reviewed ZIP state used for this correction pass, only one of those was actually present:

- `ND_Romance_Revision_Workflow_v1.0.md`

The other referenced file was **not present in the archive** and therefore was not an active overlap inside the reviewed pack state.

---

## Resolved live replacement

The correct live replacement is now:

- `ND_Readable_Romance_Revision_Workflow_v1.1.md`

This resolves the naming split for the revision layer.

---

## Archive action

### Move out of live pack

- `ND_Romance_Revision_Workflow_v1.0.md`

### Keep live

- `ND_Readable_Romance_Revision_Workflow_v1.1.md`

---

## Why archive is required

Keeping both files active would create:

- naming inconsistency
- ambiguous authority
- stale cross-reference risk
- future control drift

---

## Decision rule

Do not keep a shorter legacy-named file active when a corrected canonical replacement exists and does the same job.

---

## Resolution status

**Overlap resolved at control level. Archive move still required at file-management level.**

That means the logic is settled.
The remaining task is only to remove the superseded file from the live working pack.
