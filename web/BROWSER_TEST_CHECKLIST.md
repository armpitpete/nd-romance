# Browser Test Checklist

## File to test

```text
web/index.html
```

Open this file in a browser.

Do not add more screens until this page passes the checklist below.

---

## 1. Page loads

- [ ] Page opens without a blank screen.
- [ ] Title says `ND Romance Builder`.
- [ ] Form appears on the left or top.
- [ ] Markdown preview appears on the right or below.
- [ ] No login is requested.

Pass condition:

```text
The page opens and shows the Mini Design Sheet form.
```

---

## 2. Form input works

Type test text into these fields:

- [ ] Working title
- [ ] Romance type
- [ ] Person A name
- [ ] Person B name
- [ ] Why these two?
- [ ] Emotional promise
- [ ] Main obstacle
- [ ] External pressure
- [ ] ND-readable truth layer
- [ ] Ending requirement
- [ ] First scene seed

Pass condition:

```text
Text can be typed into every tested field.
```

---

## 3. Markdown preview updates

While typing, check the Markdown preview.

- [ ] Preview changes as text is typed.
- [ ] Preview includes the working title.
- [ ] Preview includes Person A and Person B sections.
- [ ] Preview includes external pressure.
- [ ] Preview includes first scene seed.

Pass condition:

```text
The Markdown preview updates without pressing a save button.
```

---

## 4. Browser autosave works

Steps:

1. Type a working title.
2. Type one or two other fields.
3. Refresh the browser page.

Check:

- [ ] The typed text remains after refresh.

Pass condition:

```text
The form remembers the browser draft after refresh.
```

---

## 5. Copy Markdown works

Steps:

1. Fill at least three fields.
2. Click `Copy Markdown`.
3. Paste into a text editor or note.

Check:

- [ ] Pasted text is Markdown.
- [ ] Pasted text includes the filled fields.

Pass condition:

```text
Copy Markdown places the generated Markdown on the clipboard.
```

Known possible issue:

Some browsers may block clipboard access when opening a local file directly.
If copy fails, test again after serving the file locally or through GitHub Pages.

---

## 6. Download Markdown works

Steps:

1. Fill the working title.
2. Click `Download .md`.

Check:

- [ ] A `.md` file downloads.
- [ ] Filename uses the working title.
- [ ] Downloaded file opens as plain Markdown.

Pass condition:

```text
The page downloads a usable Markdown file.
```

---

## 7. Clear form works

Steps:

1. Fill several fields.
2. Click `Clear form`.
3. Confirm the clear action.

Check:

- [ ] Form fields become empty.
- [ ] Markdown preview resets.
- [ ] Refreshing the page does not bring back the cleared text.

Pass condition:

```text
Clear form removes the current browser draft.
```

---

## 8. Mobile / narrow screen check

Narrow the browser window or open on a phone/tablet.

Check:

- [ ] Form remains readable.
- [ ] Preview moves below the form if needed.
- [ ] Buttons remain usable.
- [ ] No horizontal scrolling is needed for normal use.

Pass condition:

```text
The page remains usable on a narrow screen.
```

---

## Test verdict

After testing, record one of these:

```text
PASS — ready for GitHub Pages setup
PARTIAL — fix listed issues first
FAIL — do not add more screens yet
```

## Notes

Write any problems here:

```text
- 
- 
- 
```

---

## Next step after pass

If the checklist passes, the next useful issue is:

```text
Add GitHub Pages setup notes for web prototype
```

If it fails, create a fix issue for the specific broken behaviour.
