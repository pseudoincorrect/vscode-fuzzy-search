# VSCode Regex Search Telescope Extension

<div align="center">
  <img src="assets/images/regex-search-telescope-logo.png" alt="Regex Search Telescope Logo" width="128" height="128">
</div>

A fast and intuitive regex search extension for Visual Studio Code, inspired by vim telescope. 
Provides powerful text search capabilities with a clean split-pane (vertical) interface.

## Preview

![Regex Search Telescope Demo](assets/images/regex-search-telescope.gif)

## Functions

### 🔍 Search Current File
**Keybinding**: `Ctrl+Alt+F` (Windows/Linux) / `Cmd+Alt+F` (macOS)

Search within the currently active file with real-time regex matching and highlighting.

### 🔍 Search Workspace
**Keybinding**: `Ctrl+Alt+G` (Windows/Linux) / `Cmd+Alt+G` (macOS)

Search across all files in your workspace with blazing-fast performance.

## Configuration

### Context Size
**`regexSearch.contextSize`** (number, default: 3)

Controls how many lines of context are shown around each search result. Set the number of lines to show before and after each match (0-20). This setting controls both the content displayed in the context panel and its height, adapting automatically to show more or less context as needed.

### Search Performance Options

- **`regexSearch.maxFileSize`** (string, default: "1MB"): Maximum file size for search operations. Supports units like '500KB', '1MB', '2GB'.
- **`regexSearch.maxResults`** (number, default: 1000): Maximum number of search results to display (1-10000).

## Requirements

- **VSCode**: Version 1.74.0 or higher

## Customizing Keyboard Shortcuts

You can customize the keyboard shortcuts for this extension:

1. Open VS Code settings (`Ctrl+,` or `Cmd+,`)
2. Go to **Keyboard Shortcuts** (`Ctrl+K Ctrl+S` or `Cmd+K Cmd+S`)
3. Search for "Regex Search" to find the extension commands
4. Click the pencil icon next to any command to change its keybinding
5. Set your preferred key combination

**Available commands:**
- `Regex Search: Search in Current File` (default: `Ctrl+Alt+F` / `Cmd+Alt+F`)
- `Regex Search: Search in Current Folder` (default: `Ctrl+Alt+G` / `Cmd+Alt+G`)

---

For installation instructions, changelog, detailed usage, development setup, releases, and contribution guidelines, see [README_DEVELOPERS.md](README_DEVELOPERS.md).
