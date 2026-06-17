# ND Romance Project Status

## Current purpose

This repo holds the working Markdown source for the ND-readable romance planning and revision pack.

The pack supports romance stories that are emotionally clear, ND-readable, structurally trackable, and practical to start.

---

## Web app goal

The web app is a guided builder.

A user fills in forms, receives structured Markdown outputs, and later uses those outputs to draft the project.

Build order:

```text
forms
planning outputs
scene draft support
larger draft support later
```

Current rule: finish the form flow before adding advanced generation features.

---

## Start path

Open first:

```text
PROJECT_STATUS.md
FIRST_USE.md
HOW_TO_USE_WITH_GITHUB.md
CHANGELOG.md
VERSION_LABEL_AUDIT.md
WEB_INTERFACE_PROTOTYPE_PLAN.md
WEB_APP_PRODUCT_GOAL.md
web/README.md
web/BROWSER_TEST_CHECKLIST.md
web/LIVE_TEST_RESULT.md
```

Use the live web prototype from:

```text
https://armpitpete.github.io/nd-romance/
```

Use the Structure Spine form from:

```text
https://armpitpete.github.io/nd-romance/structure.html
```

---

## Done

- GitHub repo created.
- Active pack imported into `active_pack/`.
- First-use workflow added.
- Clean blank templates folder added.
- Quiet Hours examples added.
- Web interface prototype plan added.
- Web app product goal added.
- Static Mini Design Sheet form added.
- Static Structure Spine form added.
- Structure Spine form improved with missing fields and clearer navigation.
- GitHub Pages workflow added.
- GitHub Pages live test passed.
- Issues #1 to #27 closed.

---

## Key files

### Start files

- `README.md`
- `PROJECT_STATUS.md`
- `FIRST_USE.md`
- `HOW_TO_USE_WITH_GITHUB.md`
- `CHANGELOG.md`
- `VERSION_LABEL_AUDIT.md`
- `WEB_INTERFACE_PROTOTYPE_PLAN.md`
- `WEB_APP_PRODUCT_GOAL.md`

### Web prototype

- `web/README.md`
- `web/index.html`
- `web/structure.html`
- `web/BROWSER_TEST_CHECKLIST.md`
- `web/LIVE_TEST_RESULT.md`
- `.github/workflows/pages.yml`

### Blank templates

- `templates/README.md`
- `templates/mini_design_blank.md`
- `templates/structure_spine_blank.md`
- `templates/arc_map_blank.md`
- `templates/scene_card_blank.md`
- `templates/beat_tracker_blank.md`

---

## Known follow-up

Some active-pack filenames still say `v1.0` while the internal heading says `v1.1`.

This is documented in:

```text
VERSION_LABEL_AUDIT.md
```

---

## Next useful work

1. Test `https://armpitpete.github.io/nd-romance/structure.html` after deployment updates.
2. Add a clear link from the Mini Design page to the Structure Spine page if needed.
3. Then build the Arc Map form.

---

## Current recommendation

```text
Test the improved Structure Spine form before adding the Arc Map form.
```
