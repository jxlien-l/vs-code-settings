# VS Code Extensions & Settings
- Auto Rename Tag
- Docker
- Error Lens
- Git Graph
- Indent 4-to-2 (or can also set default indent in VS Code "Editor: Tab Size")
- indent-rainbow
- Markdown Preview
- open in browser
- Paste image (to paste images in md file)
- Postman
- Regex Previewer
- Turbo Console Log
## GO
- Go
## PHP
- PHP Debug
- PHP Intelephense
- PHP Namespace
- PHP Server
- Twig

## Settings

### Saving
```
"editor.codeActionsOnSave": {
    "source.organizeImports": true
} 
```

### HTML TWIG
```
"emmet.includeLanguages": {
    "twig": "html"
},
```

### JS
```
"javascript.suggest.autoImports": true,
"typescript.suggest.autoImports": true,
"javascript.updateImportsOnFileMove.enabled": "prompt",
"typescript.updateImportsOnFileMove.enabled": "prompt",
```

### Personnalization
```
"editor.bracketPairColorization.enabled": true,
"editor.cursorSmoothCaretAnimation": "on",
"editor.tabSize": 2,
// Brackets {} colors personalized with theme
"workbench.colorCustomizations": {
    "[One Dark Pro]": {
        "editorBracketHighlight.foreground1": "#e78009",
        "editorBracketHighlight.foreground2": "#22990a",
        "editorBracketHighlight.foreground3": "#1411c4",
        "editorBracketHighlight.foreground4": "#ddcf11",
        "editorBracketHighlight.foreground5": "#9c15c5",
        "editorBracketHighlight.foreground6": "#ffffff",
        "editorBracketHighlight.unexpectedBracket.foreground": "#FF2C6D"
    }
},
```