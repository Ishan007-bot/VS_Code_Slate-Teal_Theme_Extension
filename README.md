# Slate Teal

A calm dark theme for VS Code with a slate-navy background and teal-cyan accents.

## Palette

| Role | Hex |
|------|-----|
| Background | `#0f1720` |
| Foreground | `#c9d4e0` |
| Accent (teal) | `#4dd0c0` |
| Keywords (violet) | `#a688fa` |
| Strings (green) | `#9ece6a` |
| Functions (blue) | `#7aa2f7` |
| Numbers/constants (amber) | `#e0af68` |
| Comments (gray-blue) | `#5a6b7a` |

## Install / try it locally

1. Open this folder in VS Code.
2. Press `F5` to launch the **Extension Development Host**.
3. In the new window: `Ctrl+K Ctrl+T` → select **Slate Teal**.

## Packaging

Install the packaging tool and build a `.vsix`:

```
npm install -g @vscode/vsce
vsce package
```

Then install the generated `.vsix` via the Extensions view → `...` → **Install from VSIX**.
