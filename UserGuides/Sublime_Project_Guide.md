# 🛠️ .sublime-project Guide (for Sublime_GameModing)

---

## 📄 What is a `.sublime-project`?

This file customizes how Sublime behaves when you're working in a specific project — controlling:
- Project-specific settings
- Folders shown in sidebar
- LSP (language server) configs
- Build systems (Lua, Rust, etc.)

---

## ✅ Benefits

- No need to switch settings manually
- Always opens the right files and layout
- Adds build/run tools for game modding
- Ensures consistent dev environment

---

## 🧠 Best Practices

1. **Place it in the root** of your project repo
2. **Add it to Git** so others share the same config
3. Exclude build folders or large dirs in `folder_exclude_patterns`
4. Add useful LSP, formatting, or build system overrides
5. Use `"rulers"` to set code width guides (e.g., 80 chars)

---

## ⚙️ Customization Suggestions

| Feature           | Example                                      |
|------------------|----------------------------------------------|
| LSP               | Enable for `lua`, `rust`, or `json`         |
| Build Systems     | Run `lua`, `cargo`, or batch scripts         |
| Themes/Color      | Use `"theme"` to force a project theme       |
| TabNine Settings  | Add completions-per-language if needed       |

---

## 📁 Recommended Structure

```plaintext
Sublime_GameModing/
├── .git/
├── scripts/
├── assets/
├── docs/
├── src/
├── Sublime_GameModing.sublime-project
└── README.md
```

---

## 🚀 Load It

Open Sublime → `Project > Open Project` → select `Sublime_GameModing.sublime-project`  
Now you're working in modding mode, always.

