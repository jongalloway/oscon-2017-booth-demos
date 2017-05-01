 > The [Visual Studio Code documentation](https://code.visualstudio.com/docs/getstarted/) demonstrates a lot of top features. These are some we want to highlight, but feel free to explore.
 
 ## Welcome Screen
 
1. Launch Visual Studio Code.
1. If the Welcome screen is not already displayed (e.g. a previous solution is shown), view it by selecting *Help* / *Welcome* from the menu.

## Workspace Customization

1. In the Welcome page *Quick Links* section, click on the *Interface overview* link to show the interface overview overlay.
1. Click on the *Color theme* link and select a new color theme.
1. Click on the *Configure settings* link to bring up the settings file.
1. In the right side, add a new user setting to modify the editor.fontSize:

    ```json
    {
        "editor.fontSize": 20,
        "workbench.colorTheme": "Default High Contrast"
    }
    ```
    
 1. Save the file and note that the editor size changes immediately.
 1. Reset your user settings changes by selecting the entire contents on the right side (`settings.json`) and deleting them.
 
 ## Markdown Preview

 1. Open this repository in Visual Studio Code.
 1. Open the README.md file in the root.
 1. Open Split view using `Ctrl-\` or the split screen icon in the upper right hand corner.
 1. Show the Markdown preview using `Ctrl-Shift-V` or using the preview icon in the upper right hand corner.
 1. Demonstrate that scrolling is synchronized between the two panes.
 
 ## Source Control integration

1. Make some simple edits to this file and observe that the edits are previewed as you make them.
1. Click on the Source Control view icon in the upper left (shortcut is `Ctrl-Shift-G`).
1. Show the file differences by clicking on readme.md in the *Changes* list.
1. Undo all changes by clicking the `...` button and selecting `Discard All Changes` from the list.