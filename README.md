# Kw1c Prettier Formatter for Visual Studio Code

## Installation

Install through VS Code extensions. Search for `KW1C Prettier`

[Visual Studio Code Market Place: Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=scraayp.kw1c-prettier)

Can also be installed in VS Code: Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```
ext install scraayp.kw1c-prettier
```

## Usage

### Using Command Palette (CMD/CTRL + Shift + P)

```
1. CMD + Shift + P -> Format Document
OR
1. Select the text you want to Prettify
2. CMD + Shift + P -> Format Selection
```

### Keyboard Shortcuts

Visual Studio Code provides [default keyboard shortcuts](https://code.visualstudio.com/docs/getstarted/keybindings#_keyboard-shortcuts-reference) for code formatting. You can learn about these for each platform in the [VS Code documentation](https://code.visualstudio.com/docs/getstarted/keybindings#_keyboard-shortcuts-reference).

If you don't like the defaults, you can rebind `editor.action.formatDocument` and `editor.action.formatSelection` in the keyboard shortcuts menu of vscode.

### Format On Save

Respects `editor.formatOnSave` setting.

You can turn on format-on-save on a per-language basis by scoping the setting:

```json
// Set the default
"editor.formatOnSave": false,
// Enable per-language
"[javascript]": {
    "editor.formatOnSave": true
}
```
