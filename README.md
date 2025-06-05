# ZeroUI Discord Theme

ZeroUI is a sleek, highly customizable Discord CSS theme designed by [7xeh](https://github.com/7xeh) to enhance aesthetics, streamline UI interactions, and provide advanced control over theme variables. This README covers all key features, customization options, and usage guidance.

## 🔧 Features

### 🌈 Theming & Aesthetics

* **Modernized UI animations** with hover transitions for sidebar items and channels.
* **Spotify Player Styling** with blurred background, album art, and hover interactions.
* **Compact Context Menus** with reduced padding, icon resizing, and hover optimizations.
* **Custom Typing Indicator** replacing "typing..." with a fun "yapping" string.
* **Unread Dot Animation** turns the unread dot into a mascot head on hover.
* **Custom Loading GIF** using ShadowBuds mascot for loading screens.

### ⚙️ Sidebar Icon System

* Full icon override system for Discord's settings sidebar via CSS variables.
* Supports toggling animation, icon size, sidebar expansion, and opacity.
* Over **100+ setting icons** with permacolor support.

### 🧪 Custom Variables

Use `:root` to control theme variables:

| Variable                   | Description                 | Options           |
| -------------------------- | --------------------------- | ----------------- |
| `--discord-icon`           | Show/hide Discord logo      | `none`, `block`   |
| `--home-icon`              | Show/hide home icon         | `none`, `block`   |
| `--list-item-transition`   | Hover animation speed       | e.g., `0.2s ease` |
| `--codeblock-height`       | Max code block height       | e.g., `200px`     |
| `--add-custom-status-hide` | Show/hide status field      | `block`, `none`   |
| `--add-custom-status-text` | Replaces status placeholder | *String*          |
| `--right-gradient`         | Toggle right side gradient  | `true`, `false`   |
| `--background-width`       | Banner size                 | `full`, `half`    |
| `--tag-order`              | Position of tags            | `-1`, `0`, `1`    |
| `--status-enabled`         | Custom status bar           | `true`, `false`   |
| `--show-notes`             | Display notes section       | `true`, `false`   |

### 🖼️ Profile Enhancements

* Custom layout adjustments to new profile popouts
* Updated user banner sizing
* Status bubble styling and text injection

### 📜 Tooltips & Nitro

* Replaces default Nitro tooltips with cleaner layout
* Adds Nitro tier labels (e.g. Bronze, Gold, Ruby) to badges

### 📜 Code Block Scrollbars

* Smooth scrollbars for code blocks with custom thumb styling

### 🖼️ Icon Properties

* CSS `@property` used for modern icon customization
* Over 100+ icon bindings for Discord settings tabs with SVG URLs

## 📦 Installation

Use with any Discord CSS injector like [Vencord](https://github.com/Vendicated/Vencord).

### Method 1: Manual File Placement

1. Download the theme file: [ZeroUI.css](https://raw.githubusercontent.com/7xeh/ZeroUI/refs/heads/main/ZeroUI.css)
2. Place it in the following directory:

```\AppData\Roaming\Vencord\themes```

### Method 2: Through Discord UI
1. Open Discord settings.
2. Go to the **Themes** tab (under Vencord).
3. Click **"Open Theme Folder"**.
4. Drag and drop the downloaded `ZeroUI.css` file into that folder.

Then, enable the theme inside Vencord and reload Discord.

## 🔗 Author
Made with 💀 by **7xeh**
- Discord: `7xeh`
- GitHub: [github.com/7xeh](https://github.com/7xeh)
- Invite Link: `discord.gg/QSPhPsq9y5`

---

> *If you use this theme and like it, star the repo or drop a follow to support the work.*

```
