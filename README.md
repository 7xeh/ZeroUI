# 🎨 ZeroUI V2 — Modern Discord Theme

A **modern, sleek Discord theme** for [Vencord](https://github.com/Vencord) and [Equicord](https://github.com/Equicord) — built with cutting-edge CSS features and smooth animations.  
Experience Discord with **enhanced aesthetics, improved performance, and delightful micro-interactions**.

<div align="center">

![Version](https://img.shields.io/badge/Version-2.2.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Discord](https://img.shields.io/badge/Discord-Theme-7289da?style=for-the-badge)

</div>

---

## ✨ Features

### 🎭 **Visual Enhancements**
- 🖤 **Native-Inspired Design** — Enhances Discord's built-in themes without breaking familiarity
- 🌟 **Modern Glassmorphism** — Subtle blur effects and translucent elements
- 🎨 **Apple Emoji Support** — Complete Apple emoji replacement for consistent visuals
- 🌈 **Advanced Color System** — Smart color mixing and adaptive theming

### ⚡ **Performance & Animations**
- 🚀 **Hardware Accelerated** — Uses CSS transforms and `will-change` for smooth 60fps animations
- 🎪 **Spring Physics** — Natural, bouncy animations with cubic-bezier easing
- 📱 **Modern CSS Features** — Container queries, logical properties, and CSS Grid
- ♿ **Accessibility First** — Respects reduced motion preferences and high contrast modes

### 🎛️ **Interactive Elements**
- 🔍 **Collapsible Search Bar** — Expands on focus with smooth transitions
- 💬 **Hidden Message Actions** — Hover to reveal with spring animations
- 🎵 **Enhanced Spotify Player** — Glassmorphic design with album art backgrounds
- 📋 **Compact Context Menus** — Streamlined right-click menus with hover effects

### 🎯 **Smart UI Improvements**
- 📌 **Animated Unread Dots** — Glowing indicators with hover scaling
- 🏷️ **Guild Tag Animations** — Smooth text reveal with icon rotation
- 📝 **Compact Code Blocks** — Scrollable code with custom scrollbars
- ⏰ **Detailed Timestamps** — Full date/time information on hover

---

## 📥 Installation

### **For Vencord Users**
1. Install [Vencord](https://github.com/Vencord/Installer) if you haven't already
2. Download `ZeroUI_V2.css` from this repository
3. Place the file in your themes folder:
   ```bash
   # Windows
   %AppData%\Vencord\themes\
   
   # macOS
   ~/Library/Application Support/Vencord/themes/
   
   # Linux
   ~/.config/Vencord/themes/
   ```
4. Enable the theme in **Settings → Vencord → Themes**

### **For Equicord Users**
1. Install [Equicord](https://github.com/Equicord/Equicord) 
2. Download `ZeroUI_V2.css` from this repository
3. Place the file in your themes folder:
   ```bash
   # Windows
   %AppData%\Roaming\Equicord\themes\
   
   # macOS
   ~/Library/Application Support/Equicord/themes/
   
   # Linux
   ~/.config/Equicord/themes/
   ```
4. Enable the theme in **Settings → Equicord → Themes**

### **Quick Install via URL**
You can also install directly via URL in your client's theme settings:
```
https://raw.githubusercontent.com/7xeh/ZeroUI/main/ZeroUI_V2.css
```

---

## 🛠️ Technical Features

### **Modern CSS Architecture**
- **CSS Custom Properties** — Organized design tokens for consistent theming
- **Logical Properties** — RTL/LTR language support with `inline-size`, `block-size`
- **Container Queries** — Responsive components that adapt to their container
- **CSS Grid & Flexbox** — Modern layout techniques for better alignment

### **Performance Optimizations**
- **CSS Containment** — Optimized rendering with `contain: layout style paint`
- **Hardware Acceleration** — `transform3d()` and `will-change` for GPU rendering
- **Efficient Selectors** — Minimal specificity for faster style calculation
- **Reduced Motion Support** — Respects `prefers-reduced-motion` for accessibility

### **Animation System**
```css
/* Unified timing system */
--animation-duration-fast: 0.15s;
--animation-duration-normal: 0.25s;
--animation-duration-slow: 0.4s;

/* Physics-based easing */
--animation-easing-spring: cubic-bezier(0.175, 0.885, 0.32, 1.275);
--animation-easing-bounce: cubic-bezier(0.68, -0.55, 0.265, 1.55);
```

---

## 🎨 Customization

ZeroUI uses CSS custom properties that you can easily override:

```css
:root {
  /* Adjust animation speeds */
  --animation-duration-normal: 0.3s;
  
  /* Customize spacing */
  --spacing-md: 1.2rem;
  
  /* Modify border radius */
  --radius-lg: 1rem;
  
  /* Change unread dot size */
  --unread-size: 0.6rem;
}
```

---

## 🧩 Included Modules

- **Settings Icons** — Enhanced settings page with modern iconography
- **Synced Game Recolor** — Dynamic status colors based on activity
- **Compact Command Menu** — Streamlined command palette with transitions
- **Apple Emoji Pack** — Complete Apple emoji sprite replacement

---

## 🔄 Changelog

### **v2.2.0** (Latest)
- ✨ Complete modernization with CSS Grid and Container Queries
- 🎪 Physics-based animations with spring easing
- ♿ Enhanced accessibility with reduced motion support
- 🎨 Advanced color system with `color-mix()`
- 🚀 Performance optimizations with CSS containment

### **v2.1c**
- 🐛 Bug fixes and stability improvements
- 🎨 Visual refinements and polish

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🐛 Report Bugs** — Open an issue with detailed reproduction steps
2. **💡 Suggest Features** — Share your ideas for improvements
3. **🔧 Submit PRs** — Fork, modify, and submit pull requests
4. **📖 Improve Docs** — Help make our documentation better

### **Development Setup**
```bash
git clone https://github.com/7xeh/ZeroUI.git
cd ZeroUI
# Make your changes to ZeroUI_V2.css
# Test in Discord with live reload
```

---

## 🙏 Credits & Acknowledgments

**Core Contributors:**
- **[7xeh](https://github.com/7xeh)** — Lead Developer & Designer

**Special Thanks:**
- **[mwittrien](https://github.com/mwittrien)** — BetterDiscord plugin inspiration
- **[KrstlSkll69](https://github.com/KrstlSkll69)** — Game status recoloring
- **[acheronx0577](https://github.com/acheronx0577)** — Command menu improvements

**Community:**
- All beta testers and feedback providers
- Discord theme development community

---

## 📄 License

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.
```

---

## 📞 Support & Community

- 🐛 **Issues**: [GitHub Issues](https://github.com/7xeh/ZeroUI/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/7xeh/ZeroUI/discussions)
- 📧 **Contact**: Open an issue for direct support

---

<div align="center">

**Made with ❤️ for the Discord community**

⭐ **Star this repo if you find it useful!** ⭐

</div>
