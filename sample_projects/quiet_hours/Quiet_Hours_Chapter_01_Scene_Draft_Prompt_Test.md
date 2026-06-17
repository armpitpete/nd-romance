# Quiet Hours — Chapter 1 Scene Draft Prompt Test

## Purpose

This file tests whether the Scene Draft Prompt flow can turn a completed Scene Card into a usable drafting prompt.

Source scene:

```text
Quiet Hours — Chapter 1 — The Broken Lamp
```

---

## Generated scene draft prompt

# Quiet Hours — Scene Draft Prompt

## Task

Write a prose scene from the Scene Card below.

## Scene details

**Scene title:** The Broken Lamp

**Point of view:** Mara

**Draft length target:** 900–1,200 words

**Tone / style note:**
Quiet, restrained, concrete, emotionally clear. Keep the prose close to Mara’s perception. Use short direct sentences where needed. Let practical actions carry emotional meaning.

---

## Scene Card input

**Scene job:**
Mara discovers that Ellis can offer practical help without forcing a socially demanding exchange. The scene should establish the first safe communication pattern between them.

**Start state:**
Mara is guarded and trying to keep the lamp repair practical. She does not want to explain why the lamp matters. Ellis is careful, practical, and trying not to intrude.

**Scene conditions:**
A community building repair desk. The hallway is too loud. There is a trolley sound, office noise, and strip-light hum. Mara is managing sensory pressure while trying to complete a practical task.

**Bond evidence:**
Ellis asks one narrow practical question. He does not ask where the lamp came from. He writes the repair details and collection time on a card. He gives Mara a way to leave without more conversation.

**Misread / accuracy map:**
Mara is prepared for the interaction to become socially demanding. Ellis reads enough of the situation to keep the exchange practical. He does not claim to understand her, but his behaviour is accurate.

**Beat map:**
1. Mara arrives with the lamp hidden in a plain cotton bag.
2. She notices the repair desk sign and checks whether she has enough words.
3. Ellis looks up from a small repair job and says a normal, low-demand greeting.
4. Mara reveals the lamp but gives facts, not history.
5. Ellis asks what the lamp is doing.
6. Mara says it flickers, stops, the switch feels loose, and the plug is old.
7. Ellis checks the lamp carefully without grabbing or rushing.
8. He explains only what he can check.
9. Instead of asking personal questions, he writes the repair information on a card.
10. The card says there is no need to wait.
11. Mara leaves with the card and carries the phrase with her.

**Dialogue / subtext:**
Dialogue should be minimal. The emotional subtext is that Ellis offers a useful adjustment without making Mara perform gratitude or explain herself.

**Scene-end change:**
Mara does not yet trust Ellis fully, but she leaves with one concrete proof that he can make an interaction easier rather than harder. The phrase “No need to wait” becomes emotionally meaningful.

---

## Writing rules

- Stay in Mara’s point of view.
- Follow the beat map.
- Show care through behaviour, not explanation.
- Keep emotional meaning clear.
- Avoid vague social fog.
- Avoid melodrama.
- Do not over-explain neurodivergence.
- Use plain readable language.
- End with the required scene-end change.
- Keep the lamp history mostly hidden.

---

## Draft space

Write the scene here.

---

## Test verdict

```text
PASS WITH SMALL IMPROVEMENT NEEDED
```

The prompt is usable. It gives enough structure to draft the scene and keeps the output focused.

Small improvement needed:

```text
The draft prompt page should include a field for “hidden information / do not reveal yet”.
```

Reason:

The Quiet Hours scene depends on not explaining the lamp history too early. The draft prompt needs a direct place to preserve that instruction.

---

## Recommended next issue

```text
Add hidden-information field to Scene Draft Prompt form
```

Good enough:

- add one field to `web/draft.html`
- include it in the generated prompt
- keep everything static
- no API calls
