## Creating a new ASP.NET Core MVC application using Command Line tools

1. From the command line, run `dotnet new mvc`

## Running the application and browsing to the site using the integrated terminal in Visual Studio Code 

1. Type `code .` to launch Visual Studio Code in the current directory.
1. Open the integrated terminal using *View* / *Integrated Terminal* menu option (shortcut key: ctrl-`).
1. Run the application by typing `dotnet run` in the integrated terminal.
1. Hover over the "http://localhost:5000" line in the integrated terminal and you'll see it's a hyperlink. Ctrl-click on the link to browse the running site.

## Exploring the application code

1. Open the *Views/Home/Index.cshtml* file in Visual Studio Code.
1. Scroll to the line that reads `<h2>Application uses</h2>` and change it to something else (maybe your name).
1. Save the file.
1. Switch back to the browser and refresh to see your changes.
