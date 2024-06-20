[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15307020&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Download the Installer:

- Go to the VS Code download page and download the Windows installer.
   Run the Installer:

- Open the downloaded VSCodeSetup.exe file and allow any UAC prompts.
   Setup Wizard:

- Click Next, accept the license agreement, and click Next again.
   Select Destination Location:

- Choose the installation location (default is recommended) and click Next.
   Select Additional Tasks:

- Choose additional options like creating a desktop icon, adding context     menu actions, registering file types, and adding to PATH. Click Next.
Install:

- Click Install to start the installation.
   Complete the Installation:

- Choose to launch VS Code immediately if desired and click Finish.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   # Configure Settings:

- Theme and Appearance: 
   Choose a color theme and customize font settings.
   Tab and Whitespace Settings: Adjust indentation and tab size.
   Auto-Save: Enable auto-save for files.
   Format on Save: Enable format on save.
   Install Essential Extensions:

- Language Support: 
   Install language-specific extensions (e.g., Python, JavaScript).
   Code Linters and Formatters: Install tools like ESLint, Prettier, and Pylint.
   Version Control: Install GitLens for enhanced Git capabilities.
   Debugger: Install debugging tools for your languages.
   Snippets and Productivity Tools: Install tools like Code Spell Checker and Bracket Pair Colorizer.
   Workspace and Project Configuration:

- Workspace Settings:
  Customize settings for specific projects.
   Tasks and Build Scripts: Create tasks.json for building and running projects.
   Integrate Terminal: Use the integrated terminal for command-line tasks.
   Keybindings and Shortcuts:

- Customize Keybindings:
    Modify shortcuts to fit your workflow.
   Learn Default Shortcuts: Familiarize yourself with common shortcuts like Ctrl+Shift+P and Ctrl+P.
   Extensions for Specific Needs:

   Explore and install additional extensions from the VS Code marketplace for specific workflows.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

# Activity Bar:

   Location: Left side.
   Purpose: Quick access to views and functionalities like Explorer, Search, Source Control, Run and Debug, and Extensions.

# Side Bar:

   Location: Next to the Activity Bar.
   Purpose: Displays context-specific views such as the file explorer, search results, source control status, and extensions list.

# Editor Group:

   Location: Center.
   Purpose: Main area for writing and editing code, supporting multiple tabs, split views, and code navigation features like go to definition and IntelliSense.

# Status Bar:

   Location: Bottom.
   Purpose: Shows information about the workspace and active file, including cursor position, language mode, encoding, line endings, notifications, and Git branch status.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

# Command palette:
   The Command Palette in VS Code, accessed via Ctrl+Shift+P (or F1), allows users to perform various tasks such as opening files, running commands, installing extensions, changing settings, switching language modes, and managing keybindings efficiently.
   
# Open Files
   Type: 'Open File' to quickly open a file in your workspace.

# Run Commands:

   Type: commands like 'Git' 'Commit', 'Debug', 'Start', or Format Document to execute these actions.

# Install Extensions:

   Type: 'Extensions' Install Extensions to browse and install extensions.

# Change Settings:

   Type: 'Preferences' Open Settings to access and change user or workspace settings.
# Switch Language Mode:

   Type: 'Change Language Mode' to change the language mode of the current file.

# View and Manage Keybindings:

   Type: Preferences 'Open Keyboard Shortcuts' to view and customize keybindings.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

# Roles of extensions in VS code:
   Extensions in Visual Studio Code enhance its functionality by adding support for various programming languages, debuggers, linters, themes, and other tools that improve the development experience. They allow users to customize their coding environment to meet specific needs and workflows.

# Finding Extensions:

-  Marketplace: Go to the Extensions view by clicking the Extensions icon in  the Activity Bar or pressing Ctrl+Shift+X.
-  Search Bar: Use the search bar in the Extensions view to find specific extensions by name or keyword.
-  Categories and Recommendations: Browse through categories like “Popular”, “Installed”, and “Recommended” to discover useful extensions.

# Installing Extensions:

- Install Button: Once you find an extension, click the Install button next to it in the Extensions view.
- Command Palette: Open the Command Palette (Ctrl+Shift+P), type Extensions: Install Extensions, and select the desired extension.

# Managing Extensions:

- Enable/Disable: In the Extensions view, right-click an extension to enable or disable it.
- Uninstall: Click the Uninstall button next to an installed extension to remove it.
- Update: Extensions can be updated via the Extensions view when updates are available.

# Examples of web dev extensions:

- HTML: vscode-html-css for improved HTML support.
 -CSS: esbenp.prettier-vscode for CSS formatting and ecmel.vscode-html-css for CSS IntelliSense.
- JavaScript/TypeScript: dbaeumer.vscode-eslint for linting, esbenp.prettier-vscode for formatting, and ms-vscode.vscode-typescript-next for enhanced TypeScript support.

# Frameworks and Libraries:

- React: dsznajder.es7-react-js-snippets for React snippets, formulahendry.auto-close-tag and formulahendry.auto-rename-tag for improved JSX/HTML tag management.
- Vue: octref.vetur for Vue.js support.
- Angular: angular.ng-template for Angular tools.

# Version Control:

- GitLens: eamodio.gitlens for enhanced Git capabilities.

# Debugging:

- Debugger for Chrome: msjsdiag.debugger-for-chrome for debugging JavaScript in the Chrome browser.

# Productivity Tools:

- Live Server: ritwickdey.liveserver to launch a development local server with live reload feature.
- Path Intellisense: christian-kohler.path-intellisense for auto-completing file paths.
- Prettier: esbenp.prettier-vscode for code formatting.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

# How to Open:
   Menu: View > Terminal.
   Keyboard Shortcut: Ctrl+ (backtick)

# Using the Integrated Terminal:
- Create New Terminal: Click the + icon in the terminal tab to open a new terminal instance.
- Switch Between Terminals: Use the dropdown menu at the top of the terminal panel to switch between multiple terminal instances.
- Run Commands: You can run any command you would typically run in an external terminal, such as git, npm, pip, etc.
- Split Terminal: Click the split icon to split the terminal view and work with multiple terminal instances side by side.
- Resize Terminal: Drag the terminal panel’s edges to resize it according to your preference.

# Advantages of Using the Integrated Terminal

Convenience:
- Single environment and quick access.

Workspace Context:
- Automatic path management and consistent environment variables.

Integrated Experience:
- Synchronization with editor activities and task automation.

Customization:
- Appearance and behavior settings, different terminal profiles.

Efficiency:
- Multiple terminals, split views, and keyboard shortcuts for navigation and control.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

# Creating Files and Folders:

- New File:
Go to the File menu and select New File.
Alternatively, use the keyboard shortcut Ctrl+N (Windows/Linux) or Cmd+N (Mac).

- New Folder:
Go to the File menu and select New Folder.
Right-click in the File Explorer and select New Folder.
Use the keyboard shortcut Ctrl+Shift+N (Windows/Linux) or Cmd+Shift+N

# Opening Files and Folders:

- Open a Folder (Workspace):
Go to the File menu and select Open Folder.
Use the keyboard shortcut Ctrl+K (Windows/Linux) or Cmd+K (Mac) followed by O.
- Open a File:
Double-click the file in the File Explorer.
Use the Go to File feature (Ctrl+P or Cmd+P) and type the file name.

# Managing Files and Folders:

- File Explorer: This panel on the left side lets you browse, rename, delete, and move files/folders.
- Right-click on an item for a context menu with various options.
- Drag and Drop: Drag and drop files/folders between locations within the File Explorer to move or copy them.
- Search: Use the search bar in the File Explorer to quickly find files and folders.

# Navigating Efficiently:

- File Explorer: Quickly jump to specific folders by expanding/collapsing them in the File Explorer.
- Go to File: Use the Go to File feature (Ctrl+P or Cmd+P) to type the file name and jump to it directly.
- Recent Files: Access recently opened files from the File menu.
- Split View: Open multiple files side-by-side in a split view for easy comparison and editing.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

# Finding and Customizing Settings:

- Open the Settings editor:
  Go to File > Preferences > Settings.
  Use the keyboard shortcut Ctrl+, (Windows/Linux) or Cmd+, (Mac).
  Alternatively, use the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) and search for Preferences: Open Settings.

# Changing Theme:

- In the Settings editor, search for "Theme".
  Select the desired theme from the dropdown menu under Color Theme.
  You can also preview themes before applying them.
  
# Adjusting Font Size:

- Search for "Font Size" in the Settings editor.
  Change the value under Editor Font Size to your preference.
  This adjusts the font size for code and text elements.

# Modifying Keybindings:

- Search for "Keyboard Shortcuts" in the Settings editor.
  You can browse existing keybindings or search for a specific command.
  Click on the keybinding next to the command you want to change.
  Press the new desired key combination to set it.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

# Configure (Optional): 
- While not always necessary for simple programs, creating a launch configuration file (launch.json) is recommended for most scenarios.
This file defines how VS Code launches and debugs your program.
VS Code can often create a basic launch.json automatically, but you can customize it further.

# Set Breakpoints: 
Click on line numbers or use F9 to pause execution at specific points in your code.

# Start Debugging:
- Open the Run and Debug view (Ctrl+Shift+D/Cmd+Shift+D) and hit Run (play button) or F5.

# Debug Actions:
- Step Through Code:
F10 (Step Over): Executes current line, skipping functions.
F11 (Step Into): Executes current line, entering functions.
F12 (Step Out): Executes current line and exits the current function.

# Inspect Variables:
- View variable values in the Variables pane.
Navigate Call Stack: See the function call history in the Call Stack pane.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

# Initialize: 
- Open your project folder and initialize a Git repository (Source Control view > Initialize Repository).
# Commit:
- Edit files and stage changes (Source Control view "+" button).
  Write a clear commit message and commit (checkmark button/Ctrl+Enter/Cmd+Enter).
# Push to GitHub:
- Sign in to your GitHub account (optional but recommended).
  Link your local repository with your remote GitHub repository (Publish to GitHub).
  Push your commits to GitHub (Source Control view, up arrow button).

Citing:

- OpenAI. ChatGPT (Mar 23 version) [Large language model]. Accessed April 20, 2024. https://chat.openai.com/chat
- Microsoft. Copilot. Accessed June 20, 2024. [https://copilot.microsoft.com/]
- Google AI. Gemini. Accessed June 20, 2024. [https://gemini-ai.com/]




 Submission Guidelines
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

