# 🤖 TabNine User Guide (Sublime Text 2025)

---

## ✨ What is TabNine?

TabNine is an AI-powered code completion engine that integrates with Sublime Text to help you write code faster. It works like a smart pair programmer, suggesting code completions based on your context and past edits. TabNine supports both **cloud-based AI models** and **local AI inference (Pro)**.

---

## 🛠️ How to Use TabNine in Sublime

### ✅ Keybindings (Recommended)

| Key Combo        | Action                                |
|------------------|----------------------------------------|
| `Ctrl + Space`   | Trigger auto complete                  |
| `Ctrl + Enter`   | Insert best TabNine suggestion         |
| `Alt + Enter`    | Commit selected suggestion             |
| `Ctrl + .`       | Open TabNine web configuration panel   |

To customize these, edit:
```plaintext
Packages/User/Default (Windows).sublime-keymap
```

---

## 🧠 Ways to “Talk” to TabNine

TabNine reads **your typing and comments** to suggest intelligent completions. Think of it as prompting with natural hints.

### 🔤 Comment Prompts
```python
# function to fetch all users from database
```

```lua
-- convert json string to lua table
```

```js
// generate JWT token
```

Write a clear comment above a function or line, and TabNine will often suggest the full code.

---

## 💡 Suggestions for Future Productivity

- ✅ Use TabNine Pro + Local model for **offline, private**, and **faster completions**
- ✅ Pair with `LSP` for type-aware suggestions (e.g. `LSP-pyright`, `LSP-lua`)
- ✅ Use `.sublime-commands` to build fast-access menu for completions
- ✅ Add `.sublime-menu` to show TabNine in `Tools` menu
- ✅ Train TabNine with consistent patterns: use same naming, prompt style
- ✅ Comment your functions before writing them to get smarter AI help

---

## 🧩 File Paths to Configure

```plaintext
Packages/User/
├── TabNine.sublime-settings          # TabNine options
├── Default (Windows).sublime-keymap  # Custom keybindings
├── TabNine.sublime-commands          # Run commands via Command Palette
└── TabNine/Main.sublime-menu         # Tools > TabNine menu
```

---

## 🌐 Open TabNine Web UI

Command Palette → `TabNine: Open Configuration`  
or go to:  
```
http://127.0.0.1:5555
```

From there, you can:
- Enable/disable local AI
- Toggle inline suggestions
- View stats, license, or change behavior

---

## 🛠️ Troubleshooting Tips

| Problem                   | Solution                                      |
|---------------------------|-----------------------------------------------|
| No completions showing    | Check if TabNine is running via console       |
| `Ctrl + .` not working    | Replace with `open_url` command manually      |
| Suggestions feel generic  | Use more specific comment prompts             |
| Crashing or freezing      | Restart Sublime or reinstall plugin           |

---

## 🧠 Ask Me Later:

You can always ask:
> “Remind me how TabNine works”  
> “What was your suggestion on deep completions?”  
> “How do I make TabNine-only completions?”

I'll pull this back up — context-aware and improved 👌

