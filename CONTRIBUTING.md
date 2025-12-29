# Contributing to Obrit Icons

Thank you for considering contributing to Obrit Icons! We want to make this library as comprehensive and high-quality as possible.

## 📐 Design Guidelines

### Grid & Size
- **ViewBox**: `0 0 24 24`
- **Icon Area**: 24×24 pixels
- **Padding**: Keep 1-2px padding from edges

### Outline Style
- **Stroke Width**: 2px
- **Stroke Line Cap**: `round`
- **Stroke Line Join**: `round`
- **Stroke Color**: `currentColor`
- **Fill**: `none`

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" 
     fill="none" stroke="currentColor" stroke-width="2" 
     stroke-linecap="round" stroke-linejoin="round">
  <!-- paths here -->
</svg>
```

### Solid Style
- **Fill**: `currentColor`
- **Stroke**: `none` (omit stroke attributes)

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" 
     fill="currentColor">
  <!-- paths here -->
</svg>
```

### Style
- Modern, clean design
- Rounded corners where appropriate
- Consistent visual weight across icons
- No embedded fonts or raster images

## ➕ Adding New Icons

1. **Update CSV**: Add a new row to `icons-list.csv`:
   ```
   icon-name,icon-name,Category,n
   ```

2. **Create SVG Files**:
   - Outline: `outline/<category>/icon-name-outline.svg`
   - Solid: `solid/<category>/icon-name-solid.svg`

3. **Validate SVG**:
   - Include `xmlns="http://www.w3.org/2000/svg"`
   - No extra metadata, IDs, or classes
   - Clean, optimized paths

4. **Update CSV Status**: Change `n` to `y` when done.

5. **Submit PR**: Open a Pull Request with your changes.

## 📁 Directory Structure

```
outline/
├── general/
├── arrows/
├── media/
├── interface/
├── user/
├── communication/
├── office/
├── time/
├── location/
├── security/
├── commerce/
├── devices/
├── weather/
├── editor/
├── development/
├── finance/
├── brand/
└── shapes/
```

The `solid/` directory mirrors this structure.

## 🐛 Reporting Issues

If you find a bug or have a request for a new icon, please [open an issue](https://github.com/obraeckman/obrit-icons/issues).

## 📋 Icon Request Template

When requesting a new icon, please include:
- **Icon Name**: e.g., `calendar-plus`
- **Category**: e.g., `time`
- **Description**: Brief description of what the icon represents
- **Reference** (optional): Link to a similar icon for inspiration
