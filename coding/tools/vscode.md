# Mastering Visual Studio Code

> Visual Studio Code is a source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring.

## Extensions

- 📺 [10 Must Install Visual Studio Code Extensions](https://youtu.be/bJN1P07_lLo?list=WL)

## Tips & Tricks

- 📺 [Blazingly Fast Console.log in VSCode](https://www.youtube.com/watch?v=QbHHhLVcXNM)

## Key Bindings

```json
[
  // --> WORKBENCH <--

  {
    "key": "shift+cmd+w",
    "command": "workbench.action.closeAllEditors"
  },
  {
    "key": "cmd+o",
    "command": "workbench.action.gotoSymbol"
  },
  {
    "key": "shift+cmd+o",
    "command": "workbench.action.showAllSymbols"
  },
  {
    "key": "shift+cmd+g",
    "command": "workbench.view.scm"
  },

  // --> EDITOR <--

  {
    "key": "cmd+enter",
    "command": "editor.action.peekDefinition",
    "when": "editorHasDefinitionProvider && editorTextFocus && !inReferenceSearchEditor && !isInEmbeddedEditor"
  },
  {
    "key": "shift+cmd+enter",
    "command": "editor.action.revealDefinition",
    "when": "editorHasDefinitionProvider && editorTextFocus && !isInEmbeddedEditor"
  },
  {
    "key": "shift+cmd+d",
    "command": "editor.action.selectHighlights",
    "when": "editorFocus"
  },

  // --> GIT <--

  {
    "key": "alt+cmd+s",
    "command": "git.sync"
  },

  // --> OPEN IN GTIHUB <--

  {
    "key": "cmd+m",
    "command": "extension.copyGitHubLinkToClipboard"
  },
  {
    "key": "shift+cmd+m",
    "command": "extension.openInGitHub"
  },

  // --> PHP UNIT <--

  {
    "key": "cmd+t",
    "command": "better-phpunit.run"
  },
  {
    "key": "cmd+r",
    "command": "better-phpunit.run-suite"
  }
]
```
