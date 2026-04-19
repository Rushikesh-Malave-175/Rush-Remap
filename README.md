# ⚡ RushRemap V1.0

Gamer-style keyboard navigation for coding.

This project remaps **"I J K L"** (like WASD) into arrow key movement using `Alt`, giving you faster cursor control without leaving the home row.

Works in:
- Visual Studio Code (editor-only)
- AutoHotkey (system-wide)


## Why?

Arrow keys are far from the home row.

This lets you:
- Keep hands on home row.
- Navigate like movement keys in games (WASD → IJKL)
- Thereby increase speed and productivity


## Controls

### Basic Movement (Character)
| Key | Action |
|-----|--------|
| `Alt + I` | Move Up |
| `Alt + K` | Move Down |
| `Alt + J` | Move Left |
| `Alt + L` | Move Right |

### Word / Line Movement
| Key | Action |
|-----|--------|
| `Ctrl + Alt + J` | Move Left by Word |
| `Ctrl + Alt + L` | Move Right by Word |
| `Ctrl + Alt + I` | Go to Line Start |
| `Ctrl + Alt + K` | Go to Line End |

### Selection (Character)
| Key | Action |
|-----|--------|
| `Shift + Alt + J` | Select Left |
| `Shift + Alt + L` | Select Right |
| `Shift + Alt + I` | Select to Line Start |
| `Shift + Alt + K` | Select to Line End |

### Selection (Advanced)
| Key | Action |
|-----|--------|
| `Shift + Ctrl + Alt + J` | Select Word Left |
| `Shift + Ctrl + Alt + L` | Select Word Right |
| `Shift + Ctrl + Alt + I` | Select Up |
| `Shift + Ctrl + Alt + K` | Select Down |

---

## Visual Studio Code Setup

In VS Code,
1. Press `Ctrl + Shift + P`
2. Open: `Preferences: Open Keyboard Shortcuts (JSON)`
3. Paste your keybindings

## AutoHotkey Setup (System-wide)

Requires AutoHotKey.
1. Install AutoHotkey
2. Create a `.ahk` file
3. Paste the script
4. Run it
5. Optionally set it to autostart with windows on boot.

Now the controls work everywhere (browser, file explorer, etc.)

---

## Notes

- May conflict with some existing shortcuts
- AutoHotkey version overrides system-wide shortcuts (if any)

---

## Future Ideas

- Vim-style mode toggle  
- Custom macros (copy line, delete line, etc.)

---

## License

Free to use, modify, and improve.

---

## Author

**RushRemap by Rushikesh**

If you like this, feel free to fork or expand it.
