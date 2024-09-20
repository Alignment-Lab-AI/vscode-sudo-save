# VSCode Sudo Save Extension

This extension allows you to save files with sudo privileges when permission is denied.

## Features

- Automatically detects when a file save fails due to permission issues
- Prompts user to retry saving with sudo
- Securely handles file operations with elevated privileges
- Works on Linux, macOS, and Windows (using "Run as Administrator")

## Requirements

- VSCode version 1.60.0 or higher
- Sudo access on your system (for Linux and macOS)
- Administrator privileges (for Windows)

## Extension Settings

This extension does not add any VS Code settings.

## Known Issues

- On Windows, the sudo operation may trigger a UAC prompt
- File ownership may change when using sudo to save

## Release Notes

### 1.0.0

Initial release of VSCode Sudo Save Extension

---

## Following extension guidelines

This extension follows the [VSCode extension guidelines](https://code.visualstudio.com/api/references/extension-guidelines).

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
