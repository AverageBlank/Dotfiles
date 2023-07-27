# VSCode-AutoHotkey-Plus

AutoHotKey language support for VSCode
- [vscode-autohotkey-Plus](#vscode-autohotkey-plus)
  - [Start](#start)
  - [Debug](#debug)
  - [Language Features](#language-features)
  - [Context Menu](#context-menu)
  - [Setting](#setting)
  - [Credits](#credits)

## Start

Install  [vscode-autohotkey-plus](https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-autohotkey-plus) from vscode marketplace.

## Debug

![debug](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/debug.gif)

**Features:**
1. Click run button or press F9.
2. Support breakpoint、stacktrace、variable
4. **Output Message**: Recommend using `OutputDebug` command instead MsgBox when debug.
4. **Evalute**: Set and get variable in debug evaluter.

This extension provides basic debugging functions. If you need more debugging functions(Like **conditional breakpoint**), install additional extension [vscode-autohotkey-debug](https://marketplace.visualstudio.com/items?itemName=zero-plusplus.vscode-autohotkey-debug).

## Language Features

This extension provides basic programming language support for autohotkey:
- Method Symbol: ![methodSymbol](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/methodSymbol.png)
- Goto Definition: param, variable, method(**press ctrl then click**)
- Find References: Find method references(**shift+f12**).
- Code Format(**Shift+Alt+F**)
- Hover tip: Move mouse to method call or command. ![hover](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/hover.png)
- Code Symbol: Add two semicolon to comment code block. ![codeSymbole](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/codeSymbol.png)
- IntelliSense

## Context Menu

Support below function: ![context](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/context.png)

## Setting

OpenSetting -> extensions -> Ahk Plus
![settings](https://github.com/cweijan/vscode-autohotkey/raw/HEAD/image/settings.jpg)

## Credits
- [vscode-autohotkey](https://github.com/stef-levesque/vscode-autohotkey)