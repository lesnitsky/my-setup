# My Setup

List of apps and tools I use every day

## Code editor/IDE

[VSCode](https://code.visualstudio.com/)

- Font: [FiraCode](https://github.com/tonsky/FiraCode)
- Color theme: One Dark Pro Vivid

### VSCode extensions

- Bracket Pair Colorizer
- EditorConfig for VS Code
- Prettier
- GIthub pull requests
- Git Blame
- ESLint
- TSLint
- Sort lines
- vscode-icons
- vscode-styled-jsx
- vscode-styled-components
- React Native Tools
- Shader languages support for VS Code
- Terraform
- Polacode
- Dart
- Better TOML

### VSCode user settings

```json
{
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 14,
  "editor.renderWhitespace": "all",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.colorTheme": "One Dark Pro Vivid",
  "workbench.iconTheme": "vscode-icons",
  "window.zoomLevel": 0,
  "extensions.ignoreRecommendations": false,
  "editor.minimap.enabled": false,
  "workbench.editor.enablePreview": true,
  "explorer.confirmDragAndDrop": false,
  "typescript.autoImportSuggestions.enabled": true,
  "javascript.implicitProjectConfig.experimentalDecorators": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "breadcrumbs.enabled": true,
  "typescript.tsc.autoDetect": "off",
  "files.associations": {
    "COMMIT_EDITMSG": "markdown"
  },
  "editor.formatOnSave": true,
  "vsicons.dontShowNewVersionMessage": true,
  "prettier.eslintIntegration": true
}
```

## Terminal

[iTerm2](https://www.iterm2.com/)

### Shell

[oh-my-zsh](https://ohmyz.sh/)

#### Plugins

📄 `.zshrc`

```
plugins=(git)
```

#### Aliases

```sh
alias simulator="open /Applications/Xcode.app/Contents/Developer/Applications/Simulator.app"
alias rn="react-native"
alias dk="docker-compose"
alias gw="git commit --no-status"
```

#### Theme

[custom](https://gist.github.com/lesnitsky/25f232992f2b6eb3df50)

## Git

### GUI Tool

[GitUp](https://gitup.co/) (use it in extremly rare cases)

### Config

```
alias.st=status -s
alias.co=checkout
alias.ci=commit
alias.br=branch
alias.cian=commit --amend --no-edit
alias.ciann=commit --amend --no-edit --no-verify
alias.cp=cherry-pick
core.editor=code --wait
```

### Diff tool:

[diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)

### Merge tool

I resolve conflicts manually in VSCode

### Command line tools

- fx – `npm i -g fx`
- live-server - `npm i -g live-server`
- ngrok

## MacOS apps

- Alfred
- Spotify
- Slack
- Telegram
- Tweetbot
- Evernote
- 1Password
- Gifski
- Postman
- React Native Debugger
- Sketch
- Photoshop CC
- Lightshot Screenshot
- Spectacle
- Lungo
