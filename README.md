# vscode-settings
  ```json
  {
  "files.exclude": {
    "**/.DS_Store": true,
    "**/.git": true,
    "jspm_packages": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/*/**": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.renderWhitespace": "all",
  "editor.fontSize": 24,
  "editor.tabSize": 2,
  "editor.multiCursorModifier": "alt",
  "editor.wordWrap": "on",
  "editor.insertSpaces": true,
  "editor.fontFamily": "Fira Code Medium, monospace",
  "editor.fontLigatures": true,
  "terminal.integrated.fontFamily": "monospace",
  "terminal.integrated.fontSize": 20,

  "files.encoding": "utf8",
  "[java]": {
    "editor.defaultFormatter": "redhat.java"
  },

  "[markdown]": {
    "editor.formatOnSave": true,
    "editor.renderWhitespace": "all",
    "editor.acceptSuggestionOnEnter": "off"
  },
  "files.associations": {
    "*.jsx": "javascriptreact",
    "*.js": "javascript",
    "*html": "html",
    "*.tsx": "typescriptreact"
  },

  "editor.formatOnPaste": true,
  "[json]": {
    "editor.quickSuggestions": {
      "strings": true
    },
    "editor.suggest.insertMode": "replace",
    "gitlens.codeLens.scopes": ["document"]
  },
  "material-icon-theme.folders.theme": "specific",
  "liveServer.settings.donotShowInfoMsg": true,

  // liveSass setup
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".css",
      "savePath": "/dist"
    }
    // {
    //   "extensionName": ".min.css",
    //   "format": "compressed",
    //   "savePath": "/dist"
    // }
  ],
  // "liveSassCompile.settings.excludeList": ["**/node_modules/**", ".vscode/**"],
  "liveSassCompile.settings.generateMap": true,
  //autoprefix, will auto add perfix like -webkit- -moz-..
  "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"],
  "security.workspace.trust.untrustedFiles": "newWindow",
  "workbench.iconTheme": "material-icon-theme",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "eslint.validate": ["javascript"],
  "workbench.startupEditor": "none",
  "json.schemas": [],
  "emmet.preferences": {},
  "go.toolsManagement.autoUpdate": true,
  "html.format.contentUnformatted": "",
  "emmet.triggerExpansionOnTab": true,
  // "emmet.useInlineCompletions": true,
  "html.format.extraLiners": "",
  "[scss]": {
    "editor.suggest.insertMode": "replace",
    "gitlens.codeLens.scopes": ["document"]
  },
  "editor.formatOnSave": true,
  "js/ts.implicitProjectConfig.checkJs": true,
  "redhat.telemetry.enabled": false,
  // "workbench.colorTheme": "Default High Contrast",
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "editor.suggest.showSnippets": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.tabCompletion": "on",
  "editor.snippetSuggestions": "top",
  "editor.quickSuggestions": {
    "other": "on",
    "comments": "on",
    "strings": "on"
  },

  "workbench.colorCustomizations": {
    "activityBar.background": "#000",
    "activityBar.border": "#15ff00",
    "activityBar.activeBorder": "#15ff00",
    "panel.border": "#15ff00",
    // "activityBar.activeBackground": "#ff0000",
    // "list.hoverBackground": "#a61414",
    // "sideBar.background": "#00ff9d5a",
    "sideBar.border": "#15ff00",
    "sideBarTitle.foreground": "#15ff00",
    "titleBar.activeForeground": "#fff",
    "titleBar.inactiveForeground": "#ffffffcc",
    "titleBar.activeBackground": "#898d3f",
    // "titleBar.inactiveBackground": "#3F758DCC",
    "terminal.border": "#15ff00",
    "terminal.background": "#1d1b04",
    // "terminal.foreground": "#ff0000",
    "terminal.selectionBackground": "#ff0000",

    // "editor.background": "#000",
    //  "editor.selectionBackground": "#f2ff00",
    // "editor.selectionHighlightBorder": "#fbf300e0",
    "editor.findMatchBackground": "#f352fe8f",
    "editor.findMatchHighlightBackground": "#8e52fe9e",
    "editor.findMatchHighlightBorder": "#fbf300e0",
    "contrastBorder": "#15ff00"
  },
  "[python]": {
    "editor.formatOnType": true
  },
  "prettier.singleQuote": true,
  "files.autoSave": "afterDelay",
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "settingsSync.ignoredExtensions": ["yzane.markdown-pdf"],
  "terminal.integrated.env.osx": {},
  "[ignore]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "cmake.configureOnOpen": true,
  "code-runner.runInTerminal": true,
  "[c]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.defaultFormatter": "ms-vscode.cpptools"
  },

  "hediet.vscode-drawio.resizeImages": null,
  "excalidraw.theme": "dark",
  "tabnine.experimentalAutoImports": true,
  // other vscode settings specific to this project...
  "typescript.suggest.autoImports": true, // or
  "javascript.suggest.autoImports": true,
  "[csharp]": {
    "editor.defaultFormatter": "ms-dotnettools.csharp"
  },
  "errorLens.enabledDiagnosticLevels": ["warning", "info", "error"],
  "errorLens.enabled": true,
  "explorer.confirmDelete": false,
  "workbench.colorTheme": "GitHub Dark",
  "workbench.productIconTheme": "fluent-icons",
  "breadcrumbs.enabled": false,
  "editor.minimap.enabled": false
}


```
