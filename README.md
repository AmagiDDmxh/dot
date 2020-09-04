# dot

> Try personal infrastructure as code

## Software example

### Homebrew

```bash
brew bundle dump --describe --force --file=./Brewfile
```

### VSCode

export

```bash
code --list-extensions >> vs_code_extensions_list.txt
```

install

```bash
cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension
```

Config

 - Windows: `%USERPROFILE%\.vscode\extensions`
 - macOS/Linux: `~/.vscode/extensions`

## Refs

[Frontend Setup Guide](https://github.com/phodal/setup.guide)


[https://github.com/mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles)  🔧 .files, including ~/.macos — sensible hacker defaults for macOS 

