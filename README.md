# macos_clean_install

### Set language to English
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

### Mini apps
- spectacle `brew install --cask spectacle`
- (deprecated) nightowl https://nightowl.kramser.xyz/
- tunnelblick `brew install --cask tunnelblick`

### DEV
- vscode https://code.visualstudio.com/
- phpstorm `brew install --cask phpstorm`
- datagrip `brew install --cask datagrip`
- goland `brew install --cask goland`
- postman `brew install --cask postman`

### Node
- node `brew install node`

### Terminal
- zsh https://ohmyz.sh/
- iterm2 `brew install --cask iterm2`

### VS Code
#### Settings
```
{
    "window.zoomLevel": 1,
    "tabnine.experimentalAutoImports": true,
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "Ayu Mirage Bordered",
    "todo-tree.tree.showScanModeButton": false,
    "files.autoSave": "afterDelay",
    "editor.cursorSmoothCaretAnimation": true
}
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


