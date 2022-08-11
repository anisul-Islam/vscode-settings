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
    "editor.renderWhitespace": "all",
    "editor.fontSize": 24,
    "editor.tabSize": 2,
    "editor.multiCursorModifier": "alt",
    "editor.wordWrap": "on",
    "editor.insertSpaces": true,
    "editor.fontFamily": "Fira Code Medium, monospace",
    "editor.fontLigatures": true,
    "terminal.integrated.fontFamily": "monospace",
    "files.encoding": "utf8",
    "[typescript]": {
      "editor.formatOnSave": true,
      "editor.formatOnPaste": true
    },
    "[markdown]": {
      "editor.formatOnSave": true,
      "editor.renderWhitespace": "all",
      "editor.acceptSuggestionOnEnter": "off"
    },
    "files.associations": {
      // "*.jsx": "JavaScript React",
      "*.js": "javascriptreact",
      "*html": "html"
    },
    "editor.formatOnPaste": true,
    "vsicons.dontShowNewVersionMessage": false,
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
      "source.fixAll.eslint": true
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
    "editor.formatOnSave": true
  }

```
