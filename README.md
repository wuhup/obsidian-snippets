# Obsidian Editor Left-Align CSS Snippet

A CSS snippet for Obsidian that left-aligns your editor content while maintaining the readable line length setting.

## What This Does

By default, Obsidian centers your content when "Readable line length" is enabled. This snippet keeps the readable line width limit but aligns the content to the left side of the editor, making it easier to use the sidebar and maintaining a more traditional text editor layout.

## Features

- Left-aligns editor content while respecting the readable line width setting
- Adjustable gap between the sidebar and content (default: 3rem)
- Compatible with the Things theme's active-line indicator
- Maintains clean, readable formatting

## Installation

1. Download the `editor-left-align.css` file from this repository
2. Open your Obsidian vault folder
3. Navigate to `.obsidian/snippets/` (create the `snippets` folder if it doesn't exist)
4. Place the `editor-left-align.css` file in the snippets folder
5. In Obsidian, go to Settings → Appearance → CSS snippets
6. Find "editor-left-align" in the list and toggle it on

## Customization

You can adjust the gap between your sidebar and content by modifying the CSS variable in the snippet:

```css
:root {
  --left-align-content-gap: 3rem; /* Change this value */
}
```

Common values:
- `2rem` - Smaller gap
- `3rem` - Default, balanced spacing
- `4rem` - Larger gap for wider screens

## Requirements

- Obsidian (any recent version)
- "Readable line length" setting enabled in Settings → Editor

## Compatibility

This snippet has been tested with:
- Default Obsidian theme
- Things theme (includes special support for active-line indicator)

If you encounter issues with other themes, please open an issue.

## Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue describing the problem or enhancement
- Submit a pull request with improvements

## License

MIT License - feel free to use, modify, and share.

## Author

Created for the Obsidian community.

## Support

If you find this snippet helpful, consider:
- Starring this repository
- Sharing it with other Obsidian users
- Reporting any issues you encounter
