# Contributing to Obrit Icons

Thank you for considering contributing to Obrit Icons! We want to make this library as comprehensive and high-quality as possible.

## How to Contribute

1.  **Check the List**: specific requested icons might be listed in `icons-list.csv` with a status of `n` (No) for created.
2.  **Design Guidelines**:
    -   **Grid**: 24 x 24 pixels.
    -   **Stroke**: 2px centered stroke for outline icons.
    -   **Style**: Modern, rounded corners (where appropriate), friendly.
    -   **Format**: SVG.

## Adding New Icons

1.  **Update CSV**: Add a new row to `icons-list.csv` with the icon ID and name.
2.  **Create SVGs**:
    -   Place the outline version in `outline/<icon-id>.svg`.
    -   Place the solid version in `solid/<icon-id>-solid.svg`.
    -   Ensure the SVG content is clean (no extra metadata, IDs, or classes unless necessary).
    -   Standard ViewBox: `viewBox="0 0 24 24"`.
3.  **Submit PR**: Open a Pull Request with your changes.

## Reporting Issues

If you find a bug or have a request for a new icon, please open an issue in the repository.
