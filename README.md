[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15259524&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
 ![alt text](56666666666.png)
Go to the VS Code download page.
Click on the "Windows" download button to download the installer.
Once the download is complete, open the downloaded .exe file.
You might see a User Account Control prompt. click "Yes" to allow the installer to run.
Read and accept the license agreement.
choose the destination folder where you want to install VS Code.              
Creat a desktop icon.
Add to PATH (recommended).
Register the code as an editor for supported file types.
Add "Open with Code" action to Windows Explorer file context menu.
Click "Next" and then "Install."

![alt text](<sublime text.png>)
Go to the Sublime Text download page.
Click on the "Windows" download button to download the installer.
locate and double-click on the downloaded .exe file.
Choose the installation location.
Click "Next" and then Install.

3. Set Up Version Control System:
Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
![alt text](git.png)
Go to the Git for Windows download page. Click on windows to download 
locate and double-click the downloaded .exe file.
Click "Next" to continue through the steps.
Select the components you want to install (the default selections are usually fine).
Choose the default editor used by Git (e.g., Vim, Notepad++, or Visual Studio Code).
Adjust the PATH environment (use the recommended option )
Configure the line ending conversions (use the default ones)
Choose the terminal emulator (Git Bash is recommended so use it).
Enable the experimental options 
Click "Install."
Complete the Installation:
Once the installation is complete click "Finish.

![alt text](Github.png)

![alt text](<git hub repo.png>)
Inside your project directory, initialize a new Git repository by running: git init
Add some files in your project directory
Check the Status to see the untracked files by running: git status
Add the files to the staging area using the git add command. This prepared the files for the commit:
Commit the staged files to the repository with a commit message: git commit -m "Initial commit"
Verify the commit by viewing the commit history.
create a repository on GitHub by following these steps:
Go to GitHub and log in.
Click on the "+" icon in the upper-right corner and selected "New repository."
Enter a name for your repository and click "Create repository."
Link my your local repository to the remote repository  
Push your initial commit to the remote repository: git push -u origin master

4. Install Necessary Programming Languages and Runtimes:
Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
![alt text](python.png)
Visit the official Python download page.
Choose the Version
You will see a button to download the latest version of Python (e.g., "Download Python 3.x.x").
Click on the button to download the appropriate installer for your operating system (Windows, macOS, or Linux).
Install Python on Windows
Run the Installer
Locate the downloaded .exe file and double- click it to run the installer.
Ensure that you check the box that says "Add Python to PATH." This makes it easier to run Python from the command line.
Click on "Customize installation" if you want to customize the installation options, otherwise, click on "Install Now."
Advanced Options (optional)
If you clicked on "Customize installation," you can select optional features, choose the installation location, and add Python to environment variables.
Complete the Installation
Click "Install" and wait for the installation to complete.
Once the installation is complete, click "Close."

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Download and Install Python
Ensure you have installed Python as described in the previous steps. The Python installer for Windows includes pip by default.
Make sure to check the box that says "Add Python to PATH" during the installation process.
Verify the Installation
Open Command Prompt (search for cmd in the Start menu).
Check if pip is installed and added to PATH by running: pip --version
You should see the version of pip installed.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
![alt text](MySQL.png)
Visit the MySQL website
Go to https://dev.mysql.com/downloads/installer/.
Click on the "Download" button for the web community version.
 Run the Installer
Locate the downloaded file
Double-click the msi file to launch the MySQL Installer
Choose the setup type
The installer offers several setup types:
 choose "Developer Default".
Click "Next":
The installer will check for the necessary requirements. If any software is missing, the installer will prompt you to install it.
Install MySQL:
Review the installation summary and click "Execute". The installer will download and install the selected MySQL products and features. This process may take a few minutes.
After the installation, the MySQL Installer will guide you through the initial configuration.
Choose the type of MySQL Server you want to configure.
Select the Config Type, typically "Development Computer".
Keep the default TCP/IP port number (3306) and make sure "Open Windows Firewall port for network access" is checked.
Click "Next".
Choose the authentication method. The recommended method is "Use Strong Password Encryption.
Click "Next".
Accounts and Roles:
Set the password for the MySQL root user. Make sure to remember this password as it is required for administrative access.
Click "Next".
Configure MySQL Server as a Windows service so that it starts automatically when Windows starts.
Keep the default settings and click "Next".
Review the configuration settings and click "Execute" to apply them.
Click "Finish" once the configuration is complete.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
![alt text](docker.png)  
Go to the Docker Desktop download page.
Download the installer for Windows.
Install Docker Desktop
Run the downloaded installer.
Follow the installation instructions. You may need to restart your computer to complete the installation.
Verify the Installation:
Open a terminal or command prompt.
Check if Docker is installed correctly by running: docker --version
You should see the Docker version installed.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Visual Studio Code (VSCode)
Syntax Highlighting
Python: Python
JavaScript/TypeScript: JavaScript and TypeScript Nightly
HTML/CSS: Built-in, but can be enhanced with HTML CSS Support

Linting
ESLint: ESLint
Pylint for Python: Pylint

Code Formatting
Prettier: Prettier - Code formatter
Black (Python): Black Formatter

Version Control Integration
Git: Built-in, but enhanced with GitLens

JetBrains IntelliJ IDEA (and other JetBrains IDEs)
Syntax Highlighting
Built-in support for various languages, but can be extended with plugins like:
Rainbow Brackets: Rainbow Brackets

Linting
ESLint: Available through the JavaScript and TypeScript support.
Checkstyle for Java: CheckStyle-IDEA

Code Formatting
Integrated code formatter, but you can use additional plugins like:
Prettier: Prettier Plugin

Version Control Integration
Built-in support for Git, but can be enhanced with:
GitToolBox: GitToolBox

Other Useful Plugins
Database Navigator: Database Navigator
Key Promoter X: Key Promoter X

Sublime Text
Syntax Highlighting
Install the Package Control first to easily manage packages.
Babel: For JavaScript syntax highlighting Babel

Linting
SublimeLinter: SublimeLinter
SublimeLinter-contrib-eslint: SublimeLinter-contrib-eslint

Code Formatting
JsPrettier: JsPrettier
Python Black Formatter: Python Black

Version Control Integration
GitGutter: GitGutter
Sublime Merge: Sublime Merge Integration

Other Useful Packages
SideBarEnhancements: SideBarEnhancements
Emmet: Emmet

Atom
Syntax Highlighting
language-babel: language-babel

Linting
linter: linter
linter-eslint: linter-eslint

Code Formatting
prettier-atom: prettier-atom

Version Control Integration
git-plus: git-plus
github: Built-in GitHub package for Atom.

Other Useful Packages
atom-beautify: atom-beautify
file-icons: file-icons

Eclipse
Syntax Highlighting
Built-in for many languages, but can be extended with plugins like:
JSDT: For JavaScript JSDT

Linting
Checkstyle: Checkstyle Plug-in
SonarLint: SonarLint

Code Formatting
Integrated code formatter with customizable profiles.

Version Control Integration
EGit: EGit

Other Useful Plugins
Spring Tools: Spring Tools
Maven Integration: Maven Integration

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
This document provides step-by-step instructions for setting up a developer environment with MySQL and Visual Studio Code (VSCode). It includes the installation of MySQL, configuring VSCode, installing necessary extensions, and additional tools to enhance your development workflow.

1.Installing MySQL:
Visit the MySQL Downloads page.
Download the web community version of the MySQL Installer.
Run the Installer:
Locate the downloaded .msi file and double-click to run it.
Choose the setup type (Developer Default is recommended for most users).
Install MySQL:
Click "Next" and then "Execute" to download and install the selected MySQL products.
Follow the prompts to complete the installation.
Configure MySQL:
Configure the MySQL Server instance as a standalone server.
Set the root password and configure user accounts as needed.
Configure MySQL as a Windows service.
Apply the configuration and complete the installation.
Verify Installation:
Open the MySQL Command Line Client.
Log in with the root password and run SELECT VERSION(); to verify the installation.

2. Setting Up Visual Studio Code (VSCode)
Download VSCode:
Go to the VS Code download page.
Click on the "Windows" download button to download the installer.
Once the download is complete, open the downloaded .exe file.
You might see a User Account Control prompt. click "Yes" to allow the installer to run.
Read and accept the license agreement.
choose the destination folder where you want to install VS Code.              
Creat a desktop icon.
Add to PATH (recommended).
Register the code as an editor for supported file types.
Add "Open with Code" action to Windows Explorer file context menu.
Click "Next" and then "Install."

3.Installing and Configuring Extensions
Install Extensions:
Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or using Ctrl + Shift + X.
Search for and install the following extensions:
Python: Python
ESLint: ESLint
Prettier - Code formatter: Prettier
GitLens: GitLens
Live Server: Live Server

Configure Extensions:
Python Extension:
Open a Python file to activate the extension.
Configure Python settings, such as interpreter path, in the settings (Ctrl + ,).

ESLint:
Ensure you have eslint installed in your project (npm install eslint).
Configure ESLint settings in the .eslintrc file of your project.

Prettier:
Configure Prettier settings in the .prettierrc file of your project or in the VSCode settings.

GitLens:
Customize GitLens settings in the VSCode settings.

Live Server:
Right-click on an HTML file and select "Open with Live Server" to launch.

Additional Tools and Integrations
Node.js and npm:
Download and install Node.js from the official website.
Verify the installation by running node -v and npm -v in the terminal.

Docker:
Download and install Docker from the official website.
Verify the installation by running docker --version.

Git:
Download and install Git from the official website.
Configure Git with your user information:

4. Troubleshooting
MySQL Installation Issues:

Problem: Installation fails or MySQL service won't start.
Solution: Check for port conflicts (default port 3306). Ensure no other services are using the same port.

VSCode Extension Issues:
Problem: Extensions not working as expected.
Solution: Check the Output panel (Ctrl + Shift + U) for extension-specific logs. Reinstall the extension if necessary.

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
