# Visual Studio Code (VS Code) Installation and Navigation Guide

## Installation of VS Code

### Steps to Download and Install Visual Studio Code on Windows 11

1. **Download VS Code:**
   - Visit the [official Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button.
   - The site will automatically detect your OS and provide the appropriate download link.
   - ![1--Official-Page](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/616d0887-a9ac-4ec9-bb2f-43f83ffe5e59)

2. **Install VS Code:**
   - Run the downloaded installer (usually `VSCodeUserSetup-x64-<version>.exe`).
   - Follow the installation wizard steps:
     - Accept the license agreement.
     - Choose the installation location.
     - Select additional tasks (e.g., create a desktop icon, add to PATH, register code as an editor for supported file types).
   - Click “Install” and wait for the process to complete.
   - Once installed, you can choose to launch Visual Studio Code immediately.

### Prerequisites
- Windows 11 operating system.
- Administrator privileges to install software.
- Optionally, a Git client installed if you plan to use source control features.

## First-time Setup

### Initial Configurations and Settings

1. **Settings Sync:**
   - Go to `File > Preferences > Settings` or press `Ctrl+,`.
   - Search for "Settings Sync" and sign in with your Microsoft or GitHub account to sync settings across devices.

2. **Theme and Appearance:**
   - Open the Command Palette (`Ctrl+Shift+P`) and type `Color Theme`.
   - Choose a preferred theme from the available options.

3. **Extensions:**
   - Install essential extensions:
     - **Python:** For Python development.
     - **ESLint:** For JavaScript linting.
     - **Prettier - Code Formatter:** For code formatting.
     - **Live Server:** To launch a development local server with live reload.
     - **GitLens:** Supercharges the Git capabilities built into Visual Studio Code.

4. **Editor Settings:**
   - Configure settings for a better coding experience:
     - Auto-save files: `File > Auto Save`.
     - Adjust font size: `Ctrl+,` then search for "Font Size".
     - Enable format on save: Search for "Format On Save" in settings.

## User Interface Overview

### Main Components of the VS Code User Interface

1. **Activity Bar:**
   - Located on the far left.
   - Provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Located next to the Activity Bar.
   - Displays the content of the selected activity, such as a list of files in the Explorer or search results.

3. **Editor Group:**
   - Central area where files are opened and edited.
   - Supports multiple tabs and split views for side-by-side file editing.

4. **Status Bar:**
   - Located at the bottom of the window.
   - Displays information about the open file, such as encoding, line ending, language mode, and git branch.

## Command Palette

### Command Palette in VS Code

- Accessed by pressing `Ctrl+Shift+P` or `F1`.
- Provides a quick way to execute commands.
- Examples of common tasks:
  - **Opening Settings:** Type `Preferences: Open Settings`.
  - **Changing Theme:** Type `Color Theme` and select a theme.
  - **Running a Build Task:** Type `Tasks: Run Build Task`.

## Extensions in VS Code

### Role of Extensions

- Extend the functionality of VS Code.
- Provide language support, themes, debuggers, and tools.
  
### Finding, Installing, and Managing Extensions

1. **Finding and Installing:**
   - Go to the Extensions view by clicking the Extensions icon in the Activity Bar or press `Ctrl+Shift+X`.
   - Search for extensions using keywords.
   - Click "Install" on the desired extension.

2. **Managing Extensions:**
   - View installed extensions in the Extensions view.
   - Disable or uninstall extensions by clicking the gear icon next to the extension.

### Essential Extensions for Web Development

- **HTML CSS Support:** Provides CSS class name completion for the HTML class attribute.
- **JavaScript (ES6) code snippets:** Adds snippets for JavaScript development.
- **Path Intellisense:** Autocompletes filenames.

## Integrated Terminal

### Opening and Using the Integrated Terminal

1. **Open Terminal:**
   - Use `Ctrl+` (backtick) or go to `View > Terminal`.

2. **Using Terminal:**
   - Supports multiple terminal instances.
   - Execute commands directly within the editor.

### Advantages
- No need to switch between editor and terminal.
- Directly navigate and operate within the project directory.

## File and Folder Management

### Creating, Opening, and Managing Files and Folders

1. **Creating Files/Folders:**
   - Right-click in the Explorer view and select "New File" or "New Folder".
   - Use the `Ctrl+N` shortcut to create a new file.

2. **Opening Files/Folders:**
   - Drag and drop files/folders into the editor.
   - Use `File > Open File` or `File > Open Folder`.

3. **Managing Files/Folders:**
   - Use the Explorer to move, rename, and delete files/folders.
   - Use the breadcrumbs navigation at the top of the editor for easy navigation.

## Settings and Preferences

### Customizing Settings in VS Code

1. **Accessing Settings:**
   - Go to `File > Preferences > Settings` or press `Ctrl+,`.

2. **Changing Theme:**
   - Search for `Color Theme` in settings and select a theme.

3. **Adjusting Font Size:**
   - Search for `Font Size` and set the desired size.

4. **Customizing Keybindings:**
   - Go to `File > Preferences > Keyboard Shortcuts` or press `Ctrl+K Ctrl+S`.
   - Modify existing shortcuts or add new ones.

## Debugging in VS Code

### Setting Up and Starting Debugging

1. **Open Debug View:**
   - Click on the Debug icon in the Activity Bar or press `Ctrl+Shift+D`.

2. **Configure Debugger:**
   - Create a launch configuration by clicking on the gear icon and selecting the appropriate environment.

3. **Set Breakpoints:**
   - Click in the gutter next to the line numbers in the editor.

4. **Start Debugging:**
   - Press `F5` to start debugging.

### Key Debugging Features
- Breakpoints, step through code, watch variables, and view call stack.

## Using Source Control

### Integrating Git with VS Code

1. **Initialize Repository:**
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar.
   - Click "Initialize Repository".

2. **Making Commits:**
   - Stage changes by clicking the `+` icon next to files.
   - Enter a commit message and click the checkmark to commit.

3. **Pushing to GitHub:**
   - Use the Command Palette (`Ctrl+Shift+P`) and type `Push` to push commits to the remote repository.

By following these instructions, users can efficiently install, set up, and navigate Visual Studio Code, enhancing their coding environment and productivity.