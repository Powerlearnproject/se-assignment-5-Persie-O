[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15304712&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
SE-Assignment-5: Installation and Navigation of Visual Studio Code (VS Code)
Installation of VS Code
Steps to Download and Install Visual Studio Code on Windows 11
Prerequisites: Ensure you have Windows 11 installed on your machine.
Download:
Visit the Visual Studio Code download page.
Click on the "Windows" download link to download the VS Code installer.
Install:
Run the downloaded installer (VSCodeUserSetup-{version}.exe).
Follow the installation wizard:
Accept the license agreement.
Choose the destination folder.
Select additional tasks such as creating a desktop icon and adding to PATH.
Click "Install" and wait for the process to complete.
Once installed, launch VS Code.
First-time Setup
Initial Configurations and Settings
Theme and Appearance:
Go to File > Preferences > Color Theme and choose a theme that suits your preference (e.g., Dark+, Light+).
Extensions:
Open the Extensions view by clicking the Extensions icon in the Activity Bar or pressing Ctrl+Shift+X.
Search for and install essential extensions such as:
Python (ms-python.python)
Prettier - Code formatter (esbenp.prettier-vscode)
GitLens (eamodio.gitlens)
Live Server (ritwickdey.liveserver)
Settings:
Open settings by going to File > Preferences > Settings or pressing Ctrl+,.
Adjust settings such as font size (editor.fontSize), tab size (editor.tabSize), and auto-save (files.autoSave).
User Interface Overview
Main Components of the VS Code User Interface
Activity Bar:
Located on the far left side.
Contains icons for accessing views and commands such as Explorer, Search, Source Control, Run and Debug, and Extensions.
Side Bar:
Displays different views like Explorer, Source Control, and Extensions depending on the selected Activity Bar icon.
Used for navigating files, managing extensions, and more.
Editor Group:
Central area where you write and edit your code.
Can have multiple tabs open for different files.
Status Bar:
Located at the bottom of the window.
Provides information about the current project, file, and editor status, such as language mode, Git branch, and errors.
Command Palette
What is the Command Palette?
Definition: A powerful tool in VS Code that allows you to access and execute commands quickly.
Access: Press Ctrl+Shift+P or F1.
Examples of Common Tasks:
Change Language Mode: Type "Change Language Mode" to switch the file type.
Install Extensions: Type "Extensions: Install Extensions" to add new features.
Open Settings: Type "Preferences: Open Settings (JSON)" to modify settings directly.
Extensions in VS Code
Role and Management of Extensions
Role: Extensions add functionality to VS Code, such as language support, themes, debuggers, and tools.
Finding Extensions:
Open the Extensions view (Ctrl+Shift+X).
Search for extensions using keywords.
Installing Extensions:
Click on the desired extension and press "Install".
Managing Extensions:
View installed extensions in the Extensions view.
Disable or uninstall extensions as needed.
Examples of Essential Extensions:
Python for Python development.
Prettier for code formatting.
Live Server for a local development server with live reload.
Integrated Terminal
How to Open and Use the Integrated Terminal
Opening the Terminal:
Go to View > Terminal or press `Ctrl+`` (backtick).
Usage:
The integrated terminal opens at the bottom of the window.
Supports multiple terminal instances.
Run commands directly within VS Code, such as git status or npm install.
Advantages:
Access terminal without leaving the editor.
Simplifies workflow by integrating with the project environment.
File and Folder Management
Creating, Opening, and Managing Files and Folders
Creating:
Right-click in the Explorer view and select New File or New Folder.
Use Ctrl+N to create a new file.
Opening:
Use Ctrl+O to open a file.
Drag and drop files/folders into the Explorer view.
Managing:
Use the Explorer view to navigate and organize files.
Open multiple files in tabs and switch between them using Ctrl+Tab.
Use the breadcrumbs feature at the top of the editor to navigate directories.
Settings and Preferences
Customizing Settings
Access: Go to File > Preferences > Settings or press Ctrl+,.
Changing Settings:
Theme: Search for "Color Theme" and select a new theme.
Font Size: Search for "Font Size" and adjust the value.
Keybindings: Go to File > Preferences > Keyboard Shortcuts or press Ctrl+K Ctrl+S to modify keybindings.
Debugging in VS Code
Steps to Set Up and Start Debugging
Open Debug View: Click on the Debug icon in the Activity Bar or press Ctrl+Shift+D.
Configure Debugger:
Click on "create a launch.json file" to set up the configuration.
Select the appropriate environment (e.g., Python).
Add Breakpoints: Click in the gutter next to the line numbers to add breakpoints.
Start Debugging: Press F5 to start the debugger.
Key Debugging Features:
Breakpoints: Pause execution at specific lines.
Watch Variables: Monitor variables' values.
Call Stack: View the call stack to trace function calls.
Debug Console: Execute commands and evaluate expressions.
Using Source Control
Integrating Git with VS Code
Initialize Repository:
Open the Source Control view by clicking the Source Control icon in the Activity Bar.
Click "Initialize Repository" to create a new Git repository.
Making Commits:
Stage changes by clicking the "+" icon next to changed files.
Write a commit message and click the checkmark icon to commit.
Pushing Changes to GitHub:
Open the terminal and add the remote repository:
bash
Copy code
git remote add origin https://github.com/yourusername/your-repository.git
git push -u origin main

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

