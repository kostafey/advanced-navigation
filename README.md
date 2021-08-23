# Visual Studio Code advanced-navigation

VSCode extension in ClojureScript aimed to improve cursor navigation.

Minimal CLJS VSCode extension using shadow-cljs: 
[cljs-vscode-extension-hello-world](https://github.com/Saikyun/cljs-vscode-extension-hello-world)

## Features

* `advanced-navigation.exchangePointAndMark` - Put the selection start where 
    cursor is now, and cursor where the selection start is now.
* `advanced-navigation.forwardSexp` - Move cursor forward to pair bracket.
* `advanced-navigation.backwardSexp` - Move cursor backward to pair bracket.
* `advanced-navigation.forwardSexpSelect` - Move cursor forward to pair bracket
    and select text.
* `advanced-navigation.backwardSexpSelect` - Move cursor backward to pair bracket
    and select text.

## Quick hint

1. `npm install -g shadow-cljs`
2. `npm install`
3.  ```bash
    $ shadow-cljs clj-repl
    => (shadow/watch :dev)
    => (shadow/repl :dev)
    ```
4. Run `Command Palette`: `Calva: Connect to a Running REPL Server in the project`
* Select `shadow-cljs`
* Use `host` and `port` from `shadow-cljs clj-repl` command
* Select `:dev`.