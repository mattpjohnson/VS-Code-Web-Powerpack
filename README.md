<h1 align="center">VS Code Web Extension Powerpack</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig" style="margin-right: 8px">
    <img alt="EditorConfig logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/editorconfig.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer">
    <img alt="Output Colorizer logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/output-colorizer.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=anweber.statusbar-commands">
    <img alt="Statusbar Commands logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/statusbar-commands.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines" style="margin-right: 8px">
    <img alt="Sort lines logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/sort-lines.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense">
    <img alt="npm Intellisense logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/npm-intellisense.png" height="80">
  </a>
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=patrys.vscode-code-outline">
    <img alt="Code Outline logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/code-outline.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks">
    <img alt="Bookmarks logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/bookmarks.png" height="80">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint">
    <img alt="ESLint logo" src="https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/es-lint.png" height="80">
  </a>
</p>

## Description

This extension pack packages powerful web development extensions for Visual Studio Code.

## Extensions Included

- [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - EditorConfig Support for Visual Studio Code.
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) - Mark lines and jump to them.
- [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer) - Syntax highlighting for log files.
- [Statusbar Commands](https://marketplace.visualstudio.com/items?itemName=anweber.statusbar-commands) - Extend the statusbar with custom commands - specifically forward/back buttons.
- [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines) - Sorts lines of text.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Visual Studio Code plugin that autocompletes npm modules in import statements.
- [Code Outline](https://marketplace.visualstudio.com/items?itemName=patrys.vscode-code-outline) - A code outline tree provider for VSCode.

## Optional - Back/Forward buttons in statusbar

![Back/Forward buttons demo](https://rawgit.com/mattpjohnson/VS-Code-Web-Powerpack/master/docs/statusbar-back-forward-buttons.png)

If you'd like to add back/forward buttons to your statusbar add the following to your User Settings:<br>

```
"statusbar_command.commands": [
  {
    "text": "$(arrow-right)",
    "tooltip": "Navigate forward",
    "alignment": "right",
    "command": "workbench.action.navigateForward"
  },
  {
    "text": "$(arrow-left)",
    "tooltip": "Navigate back",
    "alignment": "right",
    "command": "workbench.action.navigateBack"
  }
]
```

## Want to see your extension added?

Open a PR and I'd be happy to take a look.

**Enjoy!**
