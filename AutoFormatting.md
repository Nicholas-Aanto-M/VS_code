# Auto-format documents
### Get prettier from vscode extensions

Ctrl + Shift + V > Settings JSON(Preference Open Workspace setting(json))

{
    "workbench.colorTheme": "Default Dark+",
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}