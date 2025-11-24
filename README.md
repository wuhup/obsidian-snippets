# Obsidian CSS Snippets

A collection of CSS snippets for Obsidian that enhance the file explorer and editor experience.

## Snippets Included

### 1. Folder Icons (`folder-icons.css`)

Enhances the Obsidian file explorer with visual folder icons while preserving the default collapse/expand chevrons.

**Features:**
- **Distinct folder icons** - Shows different icons for open and closed folders
- **Preserves chevrons** - Keeps the default collapse/expand chevron functionality intact
- **Active path highlighting** - Highlights the entire folder path of the currently active note in your theme's accent color
- **Active file highlighting** - Highlights the currently active file text in the accent color
- **Icon color sync** - Folder icons change to accent color on hover and for active paths
- **Indentation guide styling** - Active folder paths display custom indentation guide colors

**Installation:**
1. Download `folder-icons.css` from this repository
2. Open your Obsidian vault folder
3. Navigate to `.obsidian/snippets/` (create the `snippets` folder if it doesn't exist)
4. Place the `folder-icons.css` file in the snippets folder
5. In Obsidian, go to Settings → Appearance → CSS snippets
6. Find "folder-icons" in the list and toggle it on

### 2. Editor Left-Align (`editor-left-align.css`)

Left-aligns your editor content while maintaining the readable line length setting.

**Features:**
- **Left-aligned content** - Aligns editor content to the left while respecting the readable line width setting
- **Adjustable gap** - Customizable spacing between the sidebar and content (default: 3rem)
- **Theme compatibility** - Special support for the Things theme's active-line indicator
- **Clean formatting** - Maintains readable, professional appearance

**Installation:**
1. Download `editor-left-align.css` from this repository
2. Open your Obsidian vault folder
3. Navigate to `.obsidian/snippets/` (create the `snippets` folder if it doesn't exist)
4. Place the `editor-left-align.css` file in the snippets folder
5. In Obsidian, go to Settings → Appearance → CSS snippets
6. Find "editor-left-align" in the list and toggle it on

**Requirements:**
- "Readable line length" setting enabled in Settings → Editor

**Customization:**

You can adjust the gap between your sidebar and content by modifying the CSS variable:

```css
:root {
  --left-align-content-gap: 3rem; /* Change this value */
}
```

Common values:
- `2rem` - Smaller gap
- `3rem` - Default, balanced spacing
- `4rem` - Larger gap for wider screens

## Compatibility

These snippets have been tested with:
- Default Obsidian theme
- Things theme
- Prism theme

If you encounter issues with other themes, please open an issue.

## Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue describing the problem or enhancement
- Submit a pull request with improvements

## License

MIT License - feel free to use, modify, and share.

