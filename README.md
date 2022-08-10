VS Code extension which provides alternative syntax highlighting for `.properties`.

The only change so far is: do not highlight text after semicolon as comment if it's not leading:

![image](https://user-images.githubusercontent.com/6714840/184026432-65b06b11-586e-49fc-9c07-2c887e70552e.png)

This matches highlighting behaviour for `.properties` in Notepad++

Based on https://github.com/microsoft/vscode/blob/main/extensions/ini/syntaxes/ini.tmLanguage.json
