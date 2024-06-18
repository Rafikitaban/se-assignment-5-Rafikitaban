[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279298&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   I downloaded VS Code at their official webiste, https://code.visualstudio.com/. 

My operating system is windows so I followed the next procedure which was running the downloaded installer, accepted the terms of agreement and intallation options and finally completed the process. 

I then launced VS Code from my windoes start menu, customized settings, installed preferred extensions and chose  theme of my liking.

![alt text](<Screenshot 2024-06-16 060856.png>)
   

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

1. User Settings
Open settings by using command File > Preferences > Settings or press CTRL plus comma. 

In user settings you can set your preferred theme, adjust font size, enable auto-saving files among many things.

when it comes to extensions, some of the important ones include:

Python: Python extension by Microsoft for Python development.

Prettier: Code formatter supporting many languages.

GitHub Pull Requests and Issues: Integrates GitHub into VS Code.

SQLTools: Database management for various databases.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

The Activity Bar is located on the left side of the interface and its purpose is to allow you to switch between different views and activities in VS Code.

It contains icons which have the following functions:
Explorer: Shows your project files and folders.

Search: Provides search functionality within your project.

Source Control: Integrates with version control systems like Git.

Run and Debug: Helps you manage and run your code with debugging capabilities.

Extensions: Allows you to browse and install extensions to enhance VS Code's functionality.

The Side Bar is located to the right of the activity bar and its purpose is to display information and tools related to the selected activity in the Acrivity Bar. 

for example;
When the Explorer icon is selected, the Side Bar shows a file and folder explorer.

When the Search icon is selected, the Side Bar displays the search interface.

When the Source Control icon is selected, the Side Bar shows version control information and tools.

When the Extensions icon is selected, it shows the extensions marketplace and installed extensions.

The Editor Group is where you write, view and edit your code. It's purpose is to support multiple tabs, allowing you to work on several files simultaneously.

Some of the features include;
Syntax Highlighting: Colors the code based on the language to enhance readability.

IntelliSense: Provides code suggestions and autocompletion.

Code Navigation: Allows you to jump to definitions, references, and symbols within your code.

Split View: Enables you to open multiple editor panes side-by-side for better multitasking.

The Staus Bar is located at the bottom of the interface. Its purpose is to provide information and shortcuts related to your current workspace and activities.

It displays the following:
Current File Information: Shows details like the file path, line and column numbers.

Language Mode: Indicates the programming language of the currently open file and allows you to change it.

Encoding: Shows the text encoding and allows you to change it.

Line Ending: Displays the type of line endings used in the file (e.g., LF or CRLF).

Git Branch and Status: Shows the current Git branch and the status of the repository.

Notifications: Displays various status notifications and alerts.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

Opening and closing files: Type open File to quickly open a file from your project, type Close Editor to close the current editor tab.

Git Operations: Type git clone to clone a repository from a URL, Type git commit to commit staged changes with a message.

Search and Navigation: Go to Symbol and type '@' followed by a symbol name to navigate to a specific symbol in the file. Go to Line and type ':' followed by a line number to jump to a specific line in the file.

Extension Management: To install extension, type extensions: Install Extension to open the extensions marketplace and install new extensions. To disbale extension, : type Extensions: Disable to disable an installed extension.

Format Document: Type 'Format Document' to automatically format the entire document based on the language-specific rules.

Rename Symbol: Type 'Rename Symbol' to rename all instances of a symbol in the file.

Run Task: Type 'Run Task' to execute a predefined task from your tasks.json file.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

 finding, managing and installing extensions.

 In finding extensions, extensions can be found in the Visual Studio Code Marketplace. One can also search for extensions directly from VS Code using the Command Palette by typing 'Install Extensions.'

In managing extensions, you can enable or disable installed extensions by clicking on the gear icon next to each extension and selecting the appropriate option and to uninstall an extension, click the gear icon next to the extension and select Uninstall.

some of the essential extensions for web development include:

Prettier which is a code formatter and its purpose is it automatically formats your code to ensure consistency and readability.

Path Intellisense which enhances productivity  as its purpose is it  provides autocomplete suggestions for file paths in your project.

ESlint which identifies potential errors as its pupose is it highlights errors and warnings directly in the code editor.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Opening the intergrated terminal:Press Ctrl +  

Using the terminal
Command Execution: Type and execute shell commands just like you would in an external terminal.

Multiple Terminals: Create multiple terminal instances by clicking the + icon or using the dropdown menu to select a new terminal type.

Split Terminal: Split the terminal view to run multiple commands side-by-side.

Navigation: Use the terminal tabs to switch between different terminal instances.

Advantages of using integrated terminal include:
Convenience: The terminal is built into the editor, allowing seamless switching between coding and command execution without leaving VS Code.

Synchronization: The terminal automatically opens in the workspace's root directory, ensuring you're in the right context for project-specific commands.

Multitasking: Easily manage multiple terminal sessions within the same window, enhancing multitasking efficiency.

Integrated Experience: Use VS Code features like IntelliSense and command history directly in the terminal for a more integrated development workflow.

Customization: Customize the terminal's appearance and behavior to match your preferences, including themes, fonts, and shell types.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Creating Files and Folders.
In Explorer View, click the New File or New Folder icons at the top of the Explorer pane.

In Context Menu, right-click in the Explorer pane and select New File or New Folder.

In Command Palette, Use Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac), then type New File or New Folder and press Enter.

Opening Files and Folders.
In File Menu, go to File > Open File or Open Folder.

In Explorer View, double-click a file or folder in the Explorer pane to open it.

You can also Drag and Drop: Drag a file or folder from your file system into the VS Code window.

Managing Files and Folders.
Rename: Right-click on the file or folder in the Explorer pane and select Rename, or press F2 while the file or folder is selected.

Move: Drag and drop files and folders within the Explorer pane to move them.

Delete: Right-click on the file or folder and select Delete, or press Delete while the file or folder is selected.

Navigating between Files and Directories.
Explorer Pane: Use the Explorer pane to visually navigate through your project’s directory structure.

Quick Open: Press Ctrl + P (Windows/Linux) or Cmd + P (Mac) to bring up Quick Open, then start typing the name of the file you want to open.

Go to File: Press Ctrl + E (Windows/Linux) or Cmd + E (Mac) to quickly switch between recently opened files.

Breadcrumbs: Enable breadcrumbs by selecting View > Show Breadcrumbs to navigate the file hierarchy from the top of the editor.

Integrated Terminal: Use the integrated terminal to navigate using shell commands (cd, ls, dir, etc.) and open files with the code command (e.g., code filename).

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Accessing Settings.
Settings Menu: Go to File > Preferences > Settings (Windows/Linux) or Code > Preferences > Settings (Mac).

Command Palette: Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac), then type Preferences: Open Settings.

Changing Theme.
Open settings via the Settings menu or Command Palette (Preferences: Open Settings).

When Changing Theme via Command Palette, Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type Preferences: Color Theme and press Enter.
Select a theme from the list of available options.

Changing the Font Size.
Open settings via the Settings menu or Command Palette (Preferences: Open Settings).

Changing Keybindings.
Go to File > Preferences > Keyboard Shortcuts (Windows/Linux) or Code > Preferences > Keyboard Shortcuts (Mac).
Or press Ctrl + K, Ctrl + S (Windows/Linux) or Cmd + K, Cmd + S (Mac).

Use the search bar to find the command you want to rebind. Click on the existing keybinding or the + icon next to the command. Press the new key combination you want to assign. Press Enter to confirm the new keybinding.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Open the Debug view by clicking the Run and Debug icon in the Activity Bar or pressing Ctrl + Shift + D (Windows/Linux) or Cmd + Shift + D (Mac).
Select the appropriate configuration from the dropdown menu at the top.
Click the green play button or press F5 to start debugging.

Key debugging Features.
Breakpoints:Set breakpoints to pause the execution at specific lines of code. Conditional breakpoints can be set to pause only when certain conditions are met.

Watch Variables: Add variables to the Watch panel to monitor their values as you step through the code.

Call Stack: View the call stack to understand the sequence of function calls that led to the current point in execution.

Step Through Code:
Step Over (F10): Execute the next line of code, but if it’s a function call, don’t step into the function.

Step Into (F11): Step into the function call.

Step Out (Shift + F11): Step out of the current function and return to the caller.

Continue (F5): Resume execution until the next breakpoint or the end of the program.

Variable Inspection:Hover over variables in the editor to see their current values.

Debug Console: Use the Debug Console to evaluate expressions and execute commands within the current debugging context.

Exception Handling: Configure the debugger to break on exceptions. You can specify whether to break on all exceptions or only unhandled ones.

Inline Values: Display variable values inline with the code during debugging sessions for quick reference.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Make sure Git is installed on your system, then open the integrated terminal in VS Code (Ctrl + ) and type git --version to ensure Git is installed correctly.

 Open project folder: Open VS Code and navigate to File > Open Folder to open your project directory.

 Initialize git repository: Open the integrated terminal and navigate to your project folder, run the command: git init.

Alternatively, use the Source Control view by clicking the Source Control icon in the Activity Bar and then clicking the Initialize Repository button.

In the Source Control view, you'll see a list of changes (modified files). Click the + icon next to each file to stage it, or click the + icon at the top to stage all changes.

After staging the changes, enter a commit message in the message box at the top of the Source Control view.
Click the checkmark icon (✓) or press Ctrl + Enter to commit the changes.

Push to GitHub: 
Push changes using git push -u origin master or the Source Control view.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

