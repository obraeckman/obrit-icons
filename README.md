# Obrit Icons

A free, open-source set of stylish, modern SVG icons in outline and solid formats, perfect for use in web and mobile applications.

<p align="center">
  <img src="https://img.shields.io/badge/icons-354-blue" alt="Icons count">
  <img src="https://img.shields.io/badge/categories-18-green" alt="Categories">
  <img src="https://img.shields.io/github/license/obraeckman/obrit-icons" alt="License">
</p>

<p align="center">
  <a href="https://htmlpreview.github.io/?https://github.com/obraeckman/obrit-icons/blob/main/docs/icon-viewer.html">
    <img src="https://img.shields.io/badge/🔍_Preview_Icons-View_All_Icons-blue?style=for-the-badge" alt="Preview Icons">
  </a>
</p>

## ✨ Features

- **354 Icons** across 18 categories
- **Two Styles**: Outline (2px stroke) and Solid
- **Optimized**: Clean, production-ready SVG code
- **Themeable**: Uses `currentColor` for easy CSS theming
- **Open Source**: MIT License

## 📦 Categories

| Category | Icons | Category | Icons |
|----------|-------|----------|-------|
| General | 44 | Communication | 6 |
| Arrows | 20 | Office | 6 |
| Media | 19 | Security | 6 |
| Interface | 16 | Commerce | 5 |
| Weather | 9 | Devices | 5 |
| Shapes | 9 | Development | 5 |
| Editor | 8 | Location | 5 |
| User | 4 | Finance | 4 |
| Brand | 4 | Time | 2 |

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/obraeckman/obrit-icons.git
```

### Download Individual Icons

Browse the `outline/` and `solid/` directories to download specific icons.

## 📁 Structure

```
obrit-icons/
├── outline/           # Outline style icons (stroke-based)
│   ├── general/
│   ├── arrows/
│   ├── media/
│   └── ...
├── solid/             # Solid style icons (fill-based)
│   ├── general/
│   ├── arrows/
│   ├── media/
│   └── ...
└── icons-list.csv     # Complete icon inventory
```

## 💻 Usage

### HTML

```html
<!-- Inline SVG (recommended for styling) -->
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
  <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>
  <polyline points="9 22 9 12 15 12 15 22"/>
</svg>

<!-- Using <img> tag -->
<img src="outline/general/home-outline.svg" alt="Home icon" width="24" height="24">
```

### CSS

Icons use `currentColor`, so they inherit the text color:

```css
.icon {
  color: #3b82f6; /* Icon will be this blue */
  width: 24px;
  height: 24px;
}
```

### React/Vue/Angular

Copy the SVG content directly into your component, or use an SVG loader.

## 🎨 Icon Specifications

### Outline Icons
- **Stroke Width**: 2px
- **Stroke Line Cap**: Round
- **Stroke Line Join**: Round
- **Fill**: None
- **Stroke Color**: `currentColor`

### Solid Icons
- **Fill**: `currentColor`
- **Stroke**: None

### Grid
- **ViewBox**: `0 0 24 24`
- **Size**: 24×24 pixels

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

Obrit Icons is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by [Olivier Braeckman](https://github.com/obraeckman)
