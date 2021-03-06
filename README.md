# vscode-extension-js-console

> This extension is based on Ben White extension (https://github.com/whtouche/vscode-js-console-utils).

![header](images/github.png)

![](https://img.shields.io/badge/Release-v0.8.4-blue.svg?style=flat-square)
![](https://img.shields.io/badge/vscode-^1.67.0-blue.svg?style=flat-square)

## Features

VSCode extension. Easily insert console statements., by N-Iwata[(@rpf_nob)](https://twitter.com/rpf_nob)

![](images/features.gif)

## Requirements

Visual Studio Code 1.67.0 later

## Installing

This extension is available for free in the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=N-Iwata.vscode-extention-js-console)

## Usage

### basic

With selection or cursor into the variable(Anything is OK):

- Press Cmd+Shift+L => The output on a new line will be: console.log('variable: ', variable);
- Press Cmd+Shift+T => The output on a new line will be: console.table(variable);
- Press Cmd+Shift+W => The output on a new line will be: console.warn('variable: ', variable);
- Press Cmd+Shift+E => The output on a new line will be: console.error('variable: ', variable);

Without selection:

- Press Cmd+Shift+L => The output on the same line will be: console.log();
- Press Cmd+Shift+T => The output on the same line will be: console.table();
- Press Cmd+Shift+W => The output on the same line will be: console.warn();
- Press Cmd+Shift+E => The output on the same line will be: console.error();

for windows Ctrl+Shift+・・・

only .js, .jsx, .ts, .tsx, .vue, .svelte, .html file supported.

### text color

Enabled to color the text of console.log.

settings < extensions < JavaScript Insert Console < js-console.textColor

example

`console.log('%c name: ', 'color: #112233', name);`

### semicolon

Choose to have a semicolon or not.

settings < extensions < JavaScript Insert Console < js-console.endWithSemicolon

### singleQuotes

Choose single quorts or double quorts.

settings < extensions < JavaScript Insert Console < js-console.useSingleQuotes

## Contributing

### Pull requests

Feel free to make a pull request to the main branch to fix any bugs or suggestions for improvement.

### Issues

Feel free to create an issue if you have any problems or requests for improvement.

## License

[MIT License](LICENSE)
