# Merriam-Webster Search

A Simple Extension for VSCode to easily look up words in the Merriam-Webster dictionary. Adapted from [Kamesh Kotwani's Google-Search extension](https://github.com/kameshkotwani/google-search).

## What it does

If you're not sure about what a word means if you're using it correctly, you can highlight it and look it up in the [Merriam-Webster](https://www.merriam-webster.com/) dictionary.

## How it works

Simply select the word you want to search, then right click and click on `Search Webster's Dictionary` in drop-down menu.

## See it in Action

### When you select the text and right click you'll see `Search Webster's Dictionary` in your drop-down menu

![drop-down-menu](resources/drop-down-menu.png?raw=true)

### How it opens in browser

![browser-query-results](resources/search-results.png?raw=true)

### If you encounter any issues, please let me know [here](https://github.com/sgpicone/webster-search/issues)

#### This extension was made possible by [Ciprian Burca](https://github.com/burcadoruciprian) and [Kamesh Kotwani](https://github.com/kameshkotwani)

---

As of 2022-07-23 I haven't published this to the vscode marketplace, but you can clone this repo and build it using `vsce` to get a `vsix` package to install into vscode manually.

To do so, follow these steps:

- Run `npm install -g vsce`
- Run `vsce package`
- Install the package in vscode by running `code --install-extension webster-search-0.0.1.vsix`
