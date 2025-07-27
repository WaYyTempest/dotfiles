## 🎯 Main Features

- **Tiling Management** : Automatically organizes your windows
- **Workspaces** : 9 workspaces to organize your tasks
- **Smooth Navigation** : Move quickly between windows and workspaces
- **Customization** : Colored borders and visual effects

## ⌨️ Keyboard Shortcuts

### 🏠 Workspace Navigation

| Shortcut  | Action             |
| --------- | ------------------ |
| `Alt + 1` | Go to workspace 1  |
| `Alt + 2` | Go to workspace 2  |
| `Alt + 3` | Go to workspace 3  |
| `Alt + 4` | Go to workspace 4  |
| `Alt + 5` | Go to workspace 5  |
| `Alt + 6` | Go to workspace 6  |
| `Alt + 7` | Go to workspace 7  |
| `Alt + 8` | Go to workspace 8  |
| `Alt + 9` | Go to workspace 9  |
| `Alt + S` | Next workspace     |
| `Alt + A` | Previous workspace |

### 🪟 Window Management

| Shortcut                               | Action                          |
| -------------------------------------- | ------------------------------- |
| `Alt + Shift + H` or `Alt + Shift + ←` | Move window to the left         |
| `Alt + Shift + L` or `Alt + Shift + →` | Move window to the right        |
| `Alt + Shift + K` or `Alt + Shift + ↑` | Move window up                  |
| `Alt + Shift + J` or `Alt + Shift + ↓` | Move window down                |
| `Alt + Shift + Space`                  | Toggle floating mode (centered) |
| `Alt + T`                              | Toggle tiling mode              |
| `Alt + F`                              | Toggle fullscreen               |
| `Alt + M`                              | Minimize window                 |

### 🔄 Workspace Movement

| Shortcut          | Action                      |
| ----------------- | --------------------------- |
| `Alt + Shift + Q` | Move workspace to the left  |
| `Alt + Shift + D` | Move workspace to the right |
| `Alt + Shift + Z` | Move workspace up           |
| `Alt + Shift + S` | Move workspace down         |

### 📦 Move Windows to Workspaces

| Shortcut          | Action                     |
| ----------------- | -------------------------- |
| `Alt + Shift + 1` | Move window to workspace 1 |
| `Alt + Shift + 2` | Move window to workspace 2 |
| `Alt + Shift + 3` | Move window to workspace 3 |
| `Alt + Shift + 4` | Move window to workspace 4 |

### ⚙️ System Commands

| Shortcut          | Action               |
| ----------------- | -------------------- |
| `Alt + Shift + P` | Pause/Resume GlazeWM |
| `Alt + Shift + E` | Exit GlazeWM         |
| `Alt + Shift + W` | Redraw all windows   |

## 🎨 Visual Customization

### Borders

- **Active window** : Purple border (`#cba6f7`)
- **Inactive windows** : Gray border (`#a1a1a1`)

### Spacing

- **Inner gap** : 20px between windows
- **Outer gap** :
  - Top : 60px (space for taskbar)
  - Right, Bottom, Left : 20px

## 🚫 Ignored Applications

Some applications are configured to be ignored by GlazeWM:

- **zebar** - Status bar
- **yasb** - Alternative status bar
- **Bitwarden** - Password manager
- **Lightshot** - Screenshot tool
- **SnippingTool** - Windows screenshot tool
- **Cider** - Apple Music client
- **Ditto** - Advanced clipboard
- **Wallpaper Engine** - Animated wallpaper
- **PowerToys** - Microsoft system tools
- **Lively** - Animated wallpaper
- **Office Applications** - Excel, Word, PowerPoint (secondary windows)
- **Picture-in-Picture** - Browser video windows

## 💡 Usage Tips

### Recommended Workflow

1. **Organize your workspaces** : Use each workspace for a specific task

   - Workspace 1 : Web browsing
   - Workspace 2 : Development
   - Workspace 3 : Communication
   - Workspace 4 : Multimedia
   - Workspace 5 : Gaming
   - Workspace 6 : Design
   - Workspace 7 : Documentation
   - Workspace 8 : Testing
   - Workspace 9 : Miscellaneous

2. **Floating mode** : Use `Alt + Shift + Space` for windows that need a specific size

3. **Quick navigation** : Use `Alt + S` and `Alt + A` to quickly navigate between active workspaces

### Troubleshooting

- **Stuck windows** : Use `Alt + Shift + W` to redraw
- **GlazeWM not responding** : Use `Alt + Shift + P` to resume
- **Restart needed** : Use `Alt + Shift + E` to exit cleanly

## 🔧 Configuration

The configuration file is located in `config.yaml`. Main sections:

- `general` : General settings
- `gaps` : Window spacing
- `window_effects` : Visual effects
- `window_behavior` : Window behavior
- `workspaces` : Workspace definitions
- `window_rules` : Window rules
- `keybindings` : Keyboard shortcuts