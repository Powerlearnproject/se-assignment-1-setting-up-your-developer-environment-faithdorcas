[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280654&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
![alt text](<Screenshot (1206)-1.png>)
![alt text](<Screenshot (1207)-1.png>)
![alt text](<Screenshot (1208).png>)
![alt text](<Screenshot (1209).png>)
![alt text](<Screenshot (1211).png>)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   ![alt text](<Screenshot (1212).png>)
   ![alt text](<Screenshot (1214).png>)
   ![alt text](<Screenshot (1215).png>)
   ![alt text](<Screenshot (1216).png>)
   ![alt text](<Screenshot (1217).png>)
   ![alt text](<Screenshot (1218).png>)
   ![alt text](<Screenshot (1219).png>)
   ![alt text](<Screenshot (1220).png>)
   ![alt text](<Screenshot (1221).png>)
   ![alt text](<Screenshot (1222).png>)
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   ![alt text](<Screenshot (1223).png>)
   ![alt text](<Screenshot (1224).png>)
   ![alt text](<Screenshot (1225).png>)
   ![alt text](<Screenshot (1226).png>)


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  ![alt text](<Screenshot (1228).png>)
  ![alt text](<Screenshot (1230).png>)
  ![alt text](<Screenshot (1231).png>)


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   ![alt text](<Screenshot (1232).png>)
   ![alt text](<Screenshot (1231)-1.png>)
   ![alt text](<Screenshot (1245).png>)
   ![alt text](<Screenshot (1246).png>)



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   ![alt text](<Screenshot (1233).png>)
   ![alt text](<Screenshot (1234).png>)
   ![alt text](<Screenshot (1235).png>)
   ![alt text](<Screenshot (1236).png>)
   ![alt text](<Screenshot (1237).png>)
   ![alt text](<Screenshot (1238).png>)
   ![alt text](<Screenshot (1239).png>)
   ![alt text](<Screenshot (1240).png>)
   ![alt text](<Screenshot (1241).png>)
   ![alt text](<Screenshot (1242).png>)
   ![alt text](<Screenshot (1243).png>)
   ![alt text](<Screenshot (1244).png>)


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   ![alt text](<Screenshot (1248).png>)
   ![alt text](<Screenshot (1249).png>)
   ![alt text](<Screenshot (1252)-1.png>)
   ![alt text](<Screenshot (1252).png>)


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   ![alt text](<Screenshot (1253).png>)
   ![alt text](<Screenshot (1254).png>)
   ![alt text](<Screenshot (1255).png>)



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
  This comprehensive guide outlines the steps to set up your developer environment in Visual Studio Code (VS Code). It covers installing VS Code, configuring settings, integrating Git for version control, installing essential extensions, and troubleshooting common issues.

1. Installing Visual Studio Code
a. Download and Install VS Code
Download VS Code:

Go to the VS Code download page.
Choose the appropriate version for your operating system (Windows, macOS, or Linux).
Install VS Code:

Run the installer and follow the installation instructions.
Launch VS Code after the installation is complete.
2. Configuring VS Code
a. Initial Settings and Customizations
Open Settings:

Press Ctrl+, (comma) or go to File > Preferences > Settings.
Change Theme:

Open the Command Palette (Ctrl+Shift+P) and type Preferences: Color Theme.
Select a theme, such as Dark+ (default dark).
Adjust Font Size:

In the Settings view, search for Font Size and set the editor font size to your preference (e.g., 16).
Set Up Keybindings:

Open the Command Palette (Ctrl+Shift+P) and type Preferences: Open Keyboard Shortcuts.
Customize keybindings by editing the keybindings.json file:
json
Copy code
[
  {
    "key": "ctrl+s",
    "command": "workbench.action.files.save",
    "when": "editorTextFocus"
  }
]
3. Integrating Git with VS Code
a. Initializing a Git Repository
Open Your Project:

Open the folder containing your project in VS Code.
Initialize Git:

Open the Source Control view (Ctrl+Shift+G).
Click Initialize Repository or use the Command Palette (Ctrl+Shift+P) and type Git: Initialize Repository.
b. Cloning a Repository
Clone Repository:
Open the Command Palette (Ctrl+Shift+P) and type Git: Clone.
Enter the URL of the repository and choose a local directory to clone it.
4. Making Commits and Pushing Changes to GitHub
a. Making Commits
Stage Changes:

Make changes to your code.
Open the Source Control view (Ctrl+Shift+G) and click the + icon next to the changed files to stage them.
Commit Changes:

Enter a commit message and press Ctrl+Enter or click the check mark (✔️) to commit the changes.
b. Pushing to GitHub
Install GitHub Extension:

Go to Extensions view (Ctrl+Shift+X) and search for GitHub.
Install the GitHub extension provided by GitHub.
Sign In to GitHub:

Click the GitHub icon in the Activity Bar and sign in.
Push Commits:

Click the ... (more actions) button in the Source Control view and select Push.
Choose the branch to push (e.g., main) and enter your GitHub credentials if prompted.
5. Installing Essential Extensions
a. Recommended Extensions for Web Development
Prettier - Code Formatter:

Search for Prettier - Code Formatter in the Extensions view and install it.
Configure Prettier settings in settings.json:
json
Copy code
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "all"
}
ESLint:

Search for ESLint in the Extensions view and install it.
Ensure you have an .eslintrc configuration file in your project.
Debugger for Chrome:

Search for Debugger for Chrome in the Extensions view and install it.
GitLens:

Search for GitLens in the Extensions view and install it for advanced Git features.
6. Debugging in VS Code
a. Setting Up Debug Configuration
Create a Debug Configuration:

Open the Debug view (Ctrl+Shift+D).
Click on the gear icon (⚙️ Configure or Fix 'launch.json') and select the appropriate environment (e.g., Node.js).
Configure launch.json:

Replace the content with:
json
Copy code
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "program": "${workspaceFolder}/app.js"
    }
  ]
}
b. Debugging Controls
Set Breakpoints:

Click in the gutter next to the line numbers to set breakpoints.
Start Debugging:

Press F5 to start debugging.
Use F10 to step over, F11 to step into, and Shift+F11 to step out of functions.
Inspect Variables:

Hover over variables to see their values.
Use the Variables view to inspect variables.
7. Troubleshooting
a. Common Issues and Solutions
Git Not Found:

Ensure Git is installed and added to your system PATH.
Restart VS Code after installation.
Extensions Not Working:

Disable and re-enable extensions in the Extensions view.
Check for conflicting extensions.
Debugger Not Starting:

Verify the launch.json configuration.
Ensure the correct environment is selected.  


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
