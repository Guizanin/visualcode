# VScode -> extensões e configurações utilizadas

- fonte Victor Mono para *ligatures*
- [extensões](https://github.com/Guizanin/visualcode/tree/master/extensoes)
- configurações

...

    {
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.fontFamily": "Victor Mono",
  "editor.fontLigatures": true,
  "editor.lineHeight": 24,
  "editor.fontSize": 16,
  "editor.renderLineHighlight": "gutter",
  "editor.minimap.enabled": false,
  "editor.largeFileOptimizations": false,
  "workbench.sideBar.location": "left",
  "explorer.compactFolders": false,
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",

  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "editor.tabSize": 4,

  "workbench.colorCustomizations": {
    "tab.activeBackground": "#13110100"
    // "tab.activeForeground": "#8c6dbec5"
    // "activityBar.border": "#0f081bc5"
  },
  "bracket-pair-colorizer-2.colorMode": "Independent",
  "javascript.suggest.autoImports": true,
  "extensions.autoUpdate": false,
  "security.workspace.trust.untrustedFiles": "open",
  "glassit.alpha": 255,
  "glassit.step": 2,

  "sync.gist": "f41f1ab36ca90d8318eae6b78d9ee024",

  // "eslint.validate": [
  //   "javascript",
  //   "javascriptreact",
  //   { "language": "typescript", "autoFix": true },
  //   { "language": "typescriptreact", "autoFix": true }
  // ],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "workbench.iconTheme": "Monokai Pro (Filter Ristretto) Icons",
  "window.zoomLevel": 1,
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [80],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  "workbench.colorTheme": "Monokai Pro (Filter Ristretto)"
}

...
