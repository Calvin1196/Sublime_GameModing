# 🤖 TabNine AI Usage Guide

This folder documents how TabNine is used in this repo, what prompts generated what code, and how to maintain consistency across contributors.

---

## ✍️ Prompting Best Practices

- Use full-line comments like:

```lua
-- create a table of enemies with name and health
```

- TabNine works best when:
  - You comment before coding
  - You give purpose/context
  - You keep naming consistent

---

## 📚 Saved Prompts

```
# function to spawn NPC at location
-- check player inventory and return matching items
// generate a random dungeon layout
```

---

## 🧠 Completions Generated

Keep track of code TabNine helped generate here (for review, reuse, or training):

- `src/mods/inventory.lua`: auto-filled item loader
- `scripts/ai.lua`: generated combat logic (from prompt)

---

## 🔄 Future Improvements

- Log completions as comments in commits
- Add prompt snippets to this folder
- Create a prompt glossary for new contributors

