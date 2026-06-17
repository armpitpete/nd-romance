# Version Label Audit

## Purpose

This note records current filename and heading version-label mismatches in the ND Romance repo.

It exists to avoid risky mass renaming while the repo is now usable.

---

## Finding

Some active-pack files still have `v1.0` in the filename even though the internal heading or metadata now says `v1.1`.

Known examples:

- `active_pack/ND_Readable_Romance_Mini_Design_Sheet_v1.0.md`
  - internal heading: `ND Readable Romance Mini Design Sheet v1.1`
- `active_pack/ND_Readable_Romance_Scene_Card_Template_v1.0.md`
  - internal heading: `ND Readable Romance Scene Card Template v1.1`
- `active_pack/ND_Readable_Romance_Scene_Card_v1.0.md`
  - internal heading: `ND Readable Romance Scene Card v1.1`

---

## Why not rename immediately

Renaming these files now would require updating many references across:

- `README.md`
- `FIRST_USE.md`
- `PROJECT_STATUS.md`
- `CHANGELOG.md`
- active-pack index/control files
- sample-project notes

That is possible, but it is a separate cleanup pass.

It should not be mixed into the already completed setup and sample workflow work.

---

## Current decision

Do not rename files in this pass.

Keep the repo usable and stable.

Record the mismatch clearly and handle it later as a contained issue.

---

## Recommended future issue

Title:

```text
Normalize active-pack versioned filenames
```

Good enough:

- rename only the known mismatched files
- update all references in one pass
- verify `README.md`, `FIRST_USE.md`, `PROJECT_STATUS.md`, and active-pack control files
- do not change file content except references

---

## Current status

The mismatch is documented.

No workflow is blocked.

The recommended start path remains:

```text
PROJECT_STATUS.md
FIRST_USE.md
HOW_TO_USE_WITH_GITHUB.md
CHANGELOG.md
templates/
```
