# WriteLight Theme

A light theme for VSCode/Cursor optimized for writing, coding, and Claude AI interactions. Designed to provide the most comfortable reading and writing experience with carefully selected colors, typography settings, and visual enhancements.

Created by [Mat Silverstein](https://businessvacation.com)

## Features

- Soft light background that reduces eye strain
- Thoughtful color selection with a blue cursor that stands out clearly
- Optimized typography with increased line height, letter spacing, and reasonable font size
- Font ligatures enabled to enhance text flow
- Subdued but clear syntax highlighting that doesn't distract from content
- Special optimizations for markdown and prose writing
- Purple-based heading hierarchy that creates clear visual structure
- Light indentation guides that provide structure without visual noise
- Smooth cursor animation for a fluid writing experience

## Installation

### In Visual Studio Code

1. Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
2. Search for "WriteLight Theme"
3. Click Install
4. Select the theme via:
   - Command Palette (Ctrl+Shift+P or Cmd+Shift+P) → "Preferences: Color Theme" → WriteLight
   - Or via Settings → Workbench → Appearance → Color Theme → WriteLight

### In Cursor

1. Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
2. Search for "WriteLight Theme"
3. Click Install
4. Select the theme via:
   - Command Palette (Ctrl+Shift+P or Cmd+Shift+P) → "Preferences: Color Theme" → WriteLight
   - Or via Settings → Workbench → Appearance → Color Theme → WriteLight

### Manual Installation

1. Clone this repository
```
git clone https://github.com/silverstein/writelight-cursor-theme.git
```

2. Copy or symlink the entire folder to your VS Code/Cursor extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions\`
   - macOS: `~/.vscode/extensions/`
   - Linux: `~/.vscode/extensions/`

3. Restart VS Code/Cursor
4. Select the theme via the Command Palette or Settings

## Recommended Settings

For the best writing experience, these additional settings are recommended:

```json
{
  "editor.lineHeight": 1.6,
  "editor.fontSize": 14,
  "editor.letterSpacing": 0.2,
  "editor.fontFamily": "'SF Mono', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.wordWrap": "bounded",
  "editor.wordWrapColumn": 80
}
```

## Feedback

If you have any suggestions or encounter any issues, please open an issue on the [GitHub repository](https://github.com/silverstein/writelight-cursor-theme/issues).

## License

MIT 