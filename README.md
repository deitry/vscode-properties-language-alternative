VS Code extension which provides alternative syntax highlighting for `.properties`.

The only change so far is: do not highlight text after semicolon as comment if it's not leading:

```properties
; comment
    ; also comment
a=b;not a comment!
```

This matches highlighting behaviour for `.properties` in Notepad++

Based on https://github.com/microsoft/vscode/blob/main/extensions/ini/syntaxes/ini.tmLanguage.json
