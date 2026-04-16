<div align="center">

<img src="https://raw.githubusercontent.com/yorik1984/love2d-snippets/main/assets/love2d-snippets-logo512.png" alt="LÖVE snippets logo" height="256">

<h1>&nbsp;&nbsp;♡ <a href="https://love2d.org">LÖVE</a> ♡ VS Code Snippets&nbsp;&nbsp;</h1>

[![LÖVE Snippets Generator](https://github.com/yorik1984/love2d-snippets/actions/workflows/generate_love_api.yml/badge.svg)](https://github.com/yorik1984/love2d-snippets/actions/workflows/generate_love_api.yml)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yorik1984/love2d-snippets/blob/main/LICENSE)
[![Lua](https://img.shields.io/badge/Lua-5.1-blue.svg)](https://www.lua.org/)
[![LÖVE API](https://img.shields.io/badge/L%C3%96VE_API-11.5-EA316E.svg)](https://github.com/love2d-community/love-api)

</div>

This extension brings the [love2d-snippets](https://github.com/yorik1984/love2d-snippets) collection to VS Code.
For more detailed information, see the main snippets repository.

![love.load()](https://raw.githubusercontent.com/yorik1984/love2d-snippets/main/assets/love-load-vscode.gif)

## 🚀 Features
 
- **Universal snippet collection** – the generated JSON files work in any editor that supports VS Code-style snippets compatible with any VS Code snippets loader.
The `snippets/` folder contains prepared snippet JSON files for all LÖVE modules
- **Standalone script** – run in repository workflows (GitHub Actions, CI/CD, or plugin repos) to generate snippets automatically
- **GitHub Actions automation** – optional CI workflow re-runs the generator to keep snippets up to date when the official [love-api](https://github.com/love2d-community/love-api) changes
- **Full API coverage** – generates snippets for all modules, functions, callbacks, type methods, constructors, getters/setters, enums, and `conf.lua`

## 📝 What's included

- [Modules](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#modules)
- [Callbacks](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#callbacks)
- [Functions and Type methods](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#functions-and-type-methods)
- [Constructors](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#constructors)
- [Getters and setters](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#getters-and-setters)
- [Enums](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#enums) as choice snippets
- [Conf](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md#conf-snippets) snippets
- [package.json](https://github.com/yorik1984/love2d-snippets/blob/main/snippets/package.json) manifest listing the snippet files

For full instructions, see [USAGE.md](https://github.com/yorik1984/love2d-snippets/blob/main/USAGE.md).

## ⚙️ Example settings

- `editor.tabSize` – The number of spaces a tab character is displayed as.
- `editor.insertSpaces` – When enabled (true), pressing Tab inserts spaces. When disabled (false), it inserts a tab character.

```json
{
    "[lua]": {
        "editor.tabSize": 4,
        "editor.insertSpaces": true
    }
}
```

## 📜 License

MIT License

<div align="center">
  <sub>
    Built with ♡ for the LÖVE community
    <br>
    <a href="https://github.com/yorik1984/love2d-snippets-vscode/issues">Report Issue</a>·
    <a href="https://github.com/yorik1984/love2d-snippets-vscode/discussions">Discussion</a>·
    <a href="https://love2d.org/">LÖVE</a>
  </sub>
</div>
