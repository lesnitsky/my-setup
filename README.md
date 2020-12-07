# My Setup

List of apps and tools I use often

## Praimary code editor

> occasionally I use XCode and Android Studio

- VSCode
  - Font: [FiraCode](https://github.com/tonsky/FiraCode)
  - Color theme: One Dark Pro

### VSCode extensions

- Apollo GraphQL
- AWS Toolkit
- Better TOML
- Bracket Pair Colorizer
- Dart
- Dart
- EditorConfig for VS Code
- ESLint
- Flutter
- Git Blame
- Go
- Haskell
- Haskell syntax highlighting
- Kotlin Formatter
- Kotlin Language
- Polacode
- Prettier
- Pubspec Assist
- React Native Tools
- Rust
- Serverless IDE
- Shader languages support for VS Code
- Sort lines
- SQLite
- Terraform
- TSLint
- vscode-icons
- vscode-styled-components
- vscode-styled-jsx
- WakaTime

### VSCode user settings

```json
// Place your settings in this file to overwrite the default settings
{
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 14,
  "editor.renderWhitespace": "all",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.colorTheme": "One Dark Pro",
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
  "files.associations": {
    "COMMIT_EDITMSG": "markdown"
  },
  "git.autofetch": true,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "window.nativeTabs": true,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "[rust]": {
    "editor.defaultFormatter": "rust-lang.rust"
  },
  "go.useLanguageServer": true,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.iconTheme": "vscode-icons",
  "dart.warnWhenEditingFilesOutsideWorkspace": false,
  "window.newWindowDimensions": "maximized",
  "dart.debugExternalLibraries": true,
  "dart.debugSdkLibraries": true,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.confirmDelete": false,
  "haskell.formattingProvider": "stylish-haskell",
  "[yaml]": {
    "editor.defaultFormatter": "redhat.vscode-yaml"
  },
  "sqltools.useNodeRuntime": true,
  "editor.formatOnSave": true,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "aws.profile": "profile:default"
}
```

## Design Tools

- Sketch

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
alias gsf="git submodule foreach"
```

#### Theme

[custom](https://gist.github.com/lesnitsky/25f232992f2b6eb3df50)

## Git

### GUI Tool

[GitUp](https://gitup.co/)

### Config

```
[user]
	name = Andrei Lesnitsky
	email = andrei.lesnitsky@gmail.com
[alias]
	st = status -s
	co = checkout
	ci = commit
	br = branch
	cian = commit --amend --no-edit
	cp = cherry-pick
	ciann = commit --amend --no-edit --no-verify
[core]
	editor = code --wait
[commit]
	template = /Users/lesnitsky/.gitmessage
	cleanup = default
```

### Diff tool

[diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)

### Merge tool

I resolve conflicts manually in VSCode

## MacOS apps

- Spotify
- Slack
- Telegram
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
- ExpressVPN
- Blender 2
- CleanMyMac X
