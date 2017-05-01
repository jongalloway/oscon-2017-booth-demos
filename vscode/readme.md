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
 
 ## Integrated Markdown editor
 
 ## Source Control integration
