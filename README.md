# Kamailio Sublime Text Syntax

Syntax highlighting for [Kamailio](https://www.kamailio.org/) SIP server configuration files (`.cfg`, `.inc`).
Ported from [miconda/vscode-kamailio-syntax](https://github.com/miconda/vscode-kamailio-syntax) (MIT).

## Installation

### Option A – symlink (recommended for development)

```sh
# Linux
ln -s "$(pwd)" ~/.config/sublime-text/Packages/Kamailio

# macOS
ln -s "$(pwd)" ~/Library/Application\ Support/Sublime\ Text/Packages/Kamailio
```

### Option B – copy the files

```sh
# Linux
cp -r . ~/.config/sublime-text/Packages/Kamailio

# macOS
cp -r . ~/Library/Application\ Support/Sublime\ Text/Packages/Kamailio
```

Sublime Text picks up the new package automatically – no restart needed.

## Usage

- Files with `.cfg` or `.inc` extensions are detected automatically.
- Files that contain `KAMAILIO`, `SER`, `SIP-ROUTER`, or `OPENSER` on their first line are also detected regardless of extension.
- To set the syntax manually: **View → Syntax → Kamailio**

## Comment toggling

- **Line comment**: `Ctrl+/` (Win/Linux) / `⌘/` (macOS) inserts `# `
- **Block comment**: `Ctrl+Shift+/` / `⌘⌥/` inserts `/* … */`
