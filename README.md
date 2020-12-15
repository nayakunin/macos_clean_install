# macos_setup

### MacOS settings
- `sudo languagesetup` and then type 1 for English 
- Add Touch ID
- Add cyrillic keyboard
- Increase `tracking speed` by 1
- Increase `key repeat` for keyboard to fastest
- Increase `delay until repeat` to almost shortest
- Disable page navigation with two finger gesture
- Enable right mouse click with a two finger touch

### Install brew
- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- `brew update-restart`

### Browsers
- chrome `brew install --cask google-chrome`
- firefox `brew install --cask firefox`

### Apps
- slack `brew install --cask slack`
- telegram `brew install --cask telegram`
- spotify `brew install --cask spotify`
- outlook `brew install --cask microsoft-outlook`
- discord `brew install --cask discord`
- logitech options https://www.logitech.com/en-roeu/product/options

### Mini apps
- spectacle `brew install --cask spectacle`
- (deprecated) nightowl https://nightowl.kramser.xyz/
- tunnelblick `brew install --cask tunnelblick`
- scroll-reverser `brew install --cask scroll-reverser`

### DEV
- vscode `brew install --cask visual-studio-code`
- phpstorm `brew install --cask phpstorm`
- datagrip `brew install --cask datagrip`
- goland `brew install --cask goland`
- postman `brew install --cask postman`

### Languages
- node `brew install node`
- go `brew install go`

### Terminal
- zsh https://ohmyz.sh/
- iterm2 `brew install --cask iterm2`

### VS Code

#### Settings
```json
{
    "window.zoomLevel": 1,
    "tabnine.experimentalAutoImports": true,
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "Ayu Mirage Bordered",
    "todo-tree.tree.showScanModeButton": false,
    "files.autoSave": "afterDelay",
    "editor.cursorSmoothCaretAnimation": true,
    "editor.minimap.enabled": false
}
```

#### Keybinings
```json
[
    {
        "key": "ctrl+cmd+t",
        "command": "workbench.action.terminal.toggleTerminal"
    },
    {
        "key": "alt+cmd+f",
        "command": "-editor.action.startFindReplaceAction",
        "when": "editorFocus || editorIsOpen"
    }
]
```

#### Extensions
- eslint `code --install-extension dbaeumer.vscode-eslint`
- prettier `code --install-extension esbenp.prettier-vscode`
- live server `code --install-extension ritwickdey.liveserver`
- vscode-items `code --install-extension vscode-icons-team.vscode-icons`
- tabnine `code --install-extension tabnine.tabnine-vscode`
- es7 React snippets `code --install-extension dsznajder.es7-react-js-snippets`
- git graph `code --install-extension mhutchie.git-graph`
- bracket pair colorizer `code --install-extension coenraads.bracket-pair-colorizer`
- indenticator `code --install-extension sirtori.indenticator`
- ayu `code --install-extension teabyii.ayu`
- todo-tree `code --install-extension gruntfuggly.todo-tree`
- todo+ `code --install-extension fabiospampinato.vscode-todo-plus`
- visual studio keymap `code --install-extension ms-vscode.vs-keybindings`
- HTML CSS support `code --install-extension ecmel.vscode-html-css`
- color highlight `code --install-extension naumovs.color-highlight`


