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
FIRST_SCENE_DRAFT_GENERATOR_PLAN.md
web/README.md
web/BROWSER_TEST_CHECKLIST.md
web/LIVE_TEST_RESULT.md
```

Use the live web forms from:

```text
https://armpitpete.github.io/nd-romance/
https://armpitpete.github.io/nd-romance/structure.html
https://armpitpete.github.io/nd-romance/arc.html
https://armpitpete.github.io/nd-romance/scene.html
https://armpitpete.github.io/nd-romance/draft.html
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
- Static Arc Map form added.
- Static Scene Card form added.
- First scene draft generator plan added.
- Static Scene Draft Prompt form added.
- Quiet Hours Scene Draft Prompt test added.
- GitHub Pages workflow added.
- GitHub Pages live test passed.
- Issues #1 to #32 closed.

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
- `FIRST_SCENE_DRAFT_GENERATOR_PLAN.md`

### Web prototype

- `web/README.md`
- `web/index.html`
- `web/structure.html`
- `web/arc.html`
- `web/scene.html`
- `web/draft.html`
- `web/BROWSER_TEST_CHECKLIST.md`
- `web/LIVE_TEST_RESULT.md`
- `.github/workflows/pages.yml`

### Sample tests

- `sample_projects/quiet_hours/Quiet_Hours_Chapter_01_Scene_Draft_Prompt_Test.md`

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

1. Add a hidden-information field to `web/draft.html`.
2. Include it in the generated prompt.
3. Keep the page static.
4. Do not add API calls yet.

---

## Current recommendation

```text
Add hidden-information field to Scene Draft Prompt form.
```
