# Try VS Code Extensions on Codespaces

The idea of this repo is to be a place where I can test any VS Code extension on Codespaces.

At first, I'll try my own extensions, but it will not be limited to this. I use some extensions on my daily basis so I'll definitely need to know if I can use it on Codespaces.

## Results

Extension | Status | Details
--------- | ------ | -------
[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | ✅
[Copy Word in Cursor](https://marketplace.visualstudio.com/items?itemName=alefragnani.copy-word) | ❌ | _doesn't copy the content do clipboard_ ([issue #18](https://github.com/alefragnani/vscode-copy-word/issues/18))
[Delphi Extension Pack](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-pack) | ✅
[Delphi Keymap](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-keybindings) | ❌ | _unable to install the extension_ ([issue #16](https://github.com/alefragnani/vscode-delphi-keybindings/issues/16))
[Delphi Themes](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-themes) | ✅
[Jenkins Status](https://marketplace.visualstudio.com/items?itemName=alefragnani.jenkins-status) | ✅
[Pascal](https://marketplace.visualstudio.com/items?itemName=alefragnani.pascal) | 🟡 | _only syntax highlight and snippets works! code navigation requires tools to be on Codespaces_ ([issue #66](https://github.com/alefragnani/vscode-language-pascal/issues/66))
[Pascal Formatter](https://marketplace.visualstudio.com/items?itemName=alefragnani.pascal-formatter) | ❌ | _requires  FreePascal PtoP to be installed on Codespaces_ ([issue #24](https://github.com/alefragnani/vscode-pascal-formatter/issues/24))
[RTF](https://marketplace.visualstudio.com/items?itemName=alefragnani.rtf) | ✅
[Numbered Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.numbered-bookmarks) | ✅
[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) | ✅
[Read-only Indicator](https://marketplace.visualstudio.com/items?itemName=alefragnani.read-only-indicator) | 🟡 | _correctly shows the file attribute, but doesn't change it when requested_ ([issue #31](https://github.com/alefragnani/vscode-read-only-indicator/issues/31))
[Tagged Comment](https://marketplace.visualstudio.com/items?itemName=alefragnani.tagged-comment) | ✅

### Legend of annotations:

Mark | Description
---- | -----------
✅ | working
❌ | not working
🟡 | some features missing
🏃 | work in progress

## Hosts

I'm using a MacMini running MacOS Catalina and an iPad, both on Safari.

# License

[MIT](LICENSE.md) &copy; Alessandro Fragnani