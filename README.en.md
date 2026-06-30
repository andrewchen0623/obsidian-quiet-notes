# Obsidian Quiet Notes

A quiet, lightweight CSS snippet for Obsidian, designed for comfortable Chinese writing, daily notes, and card-like reading.

[中文说明](README.md)

Quiet Notes is not a full Obsidian theme or plugin. It is a small CSS snippet that adjusts typography, spacing, tables, highlights, blockquotes, and light/dark color variables while keeping Obsidian's app layout untouched.

The main design principle is: **improve the writing and reading experience inside note content, without interfering with Obsidian's own interface layout.**

## Who Is It For

- People who write Chinese long-form notes, journals, or card-style notes in Obsidian
- People who want a quieter and more comfortable reading rhythm
- People who want a lightweight visual adjustment without switching to a full theme
- People who prefer a CSS file that is easy to read, edit, and customize

## Features

- Chinese-friendly typography
- Better paragraph and heading rhythm
- Cleaner tables
- Softer highlights and blockquotes
- Light and dark mode variables
- Scoped content rules to avoid breaking Obsidian sidebars and UI components

## Installation

### Recommended: Install With An Agent

If you already use Codex, Claude Code, Cursor, Gemini CLI, or another local agent, copy the instruction below and send it to your agent:

```text
Please install this Obsidian CSS Snippet: https://github.com/andrewchen0623/obsidian-quiet-notes
```

Your agent can read this README and follow the installation instructions. You only need to refresh and enable `quiet-notes` in Obsidian.

### Manual Installation

1. Download `quiet-notes.css`.
2. Open your Obsidian vault folder.
3. Copy `quiet-notes.css` into:

```text
.obsidian/snippets/
```

4. In Obsidian, open `Settings` -> `Appearance`.
5. Scroll to `CSS snippets`.
6. Click the refresh button, then enable `quiet-notes`.

If the `snippets` folder does not exist, create it manually under `.obsidian`.

## Screenshots

### Overall Reading Experience

![Quiet Notes before and after overview](assets/screenshots/overview-before-after.png)

### Long Notes And Highlights

![Quiet Notes long note before and after](assets/screenshots/long-note-before-after.png)

### Tables

![Quiet Notes table before and after](assets/screenshots/table-before-after.png)

### Detail View

![Quiet Notes highlight and spacing before and after](assets/screenshots/highlight-spacing-before-after.png)

## Files

- `quiet-notes.css`: the main CSS snippet
- `README.md`: Chinese README
- `assets/screenshots/`: screenshot examples

## Notes

This project is intended to stay small and easy to understand. It is not an Obsidian community plugin, and it is not yet an Obsidian community theme.

If the snippet becomes useful to more people, it may later evolve into a full Obsidian Community Theme.

## Contributors

- Andrew: visual design, usage experience, and project maintenance
- OpenAI Codex: project organization, documentation collaboration, and open-source publishing

## License

MIT
