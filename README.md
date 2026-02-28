# VS Code — DoubleTrees Sepia

A warm parchment/sepia **light** theme for VS Code, aligned with the DoubleTrees Sepia palette (Ghostty + Obsidian).

## What’s included

- `package.json` — VS Code theme extension manifest
- `themes/doubletrees-sepia-color-theme.json` — UI + token colors

## Local install (recommended)

This repo is designed to be cloned onto new machines and installed locally.

### Install from an existing .vsix (fast)

If you already have a VSIX file:

```bash
/usr/bin/code --install-extension /full/path/to/doubletrees-sepia-1.0.2.vsix
```

### Install by packaging from this repo (clean, reproducible)

This requires `vsce`:

```bash
/usr/bin/npm install -g @vscode/vsce
```

Then from the repo:

```bash
/usr/bin/cd /home/zk/projects/vscode-doubletrees-sepia
/usr/bin/vsce package
/usr/bin/code --install-extension ./*.vsix
```

## Update (quick)

```bash
/usr/bin/git -C /home/zk/projects/vscode-doubletrees-sepia pull
```

Then re-package and reinstall the newly built `.vsix`.

## Notes

- Theme type is **light** (`uiTheme: vs`).
- Keep the palette consistent with the Ghostty + Obsidian versions.
