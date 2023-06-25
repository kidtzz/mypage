---
title: "Setting Json Vscode"
date: 2023-06-25T20:53:12+07:00
draft: false
tags: [vscode, json, setting]
ShareButtons: ["linkedin","whatsapp","twitter"]
ShowReadingTime: true
---

**vscode beautiful setup settings.json **

```
{
  "glassit.alpha": 245,
  "workbench.sideBar.location": "right",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Monokai Pro",
  "git.suggestSmartCommit": false,
  "redhat.telemetry.enabled": true,
  "terminal.integrated.cursorBlinking": true,
  "editor.cursorBlinking": "expand",
  "editor.fontFamily": "Cascadia Code, monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 12.5,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.guides.bracketPairs": true,
  "editor.renderWhitespace": "all",
  "editor.semanticHighlighting.enabled": true,
  "editor.snippetSuggestions": "top",
  "editor.stickyScroll.enabled": true,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.wordWrap": "wordWrapColumn",
  "editor.accessibilitySupport": "off",
  "editor.bracketPairColorization.enabled": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 500,
  "files.exclude": {
    "**/*.js.map": {
      "when": "$(basename)"
    },
    "**/node_modules": false
  },
  "eslint.alwaysShowStatus": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "emmet.includeLanguages": {
    "markdown": "html",
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "html",
    "typescript": "html"
  },
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.triggerExpansionOnTab": true,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
    "editor.formatOnSave": true
  },
  "[javascript, javascriptreact, typescript, scss, jsonc]": {
    "editor.formatOnSave": false
  },
  "autoprefixer.options": {
    "browsers": [
      "last 4 versions",
      "ie >= 9",
      "> 5%"
    ]
  }
}
```