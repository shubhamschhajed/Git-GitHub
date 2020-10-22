## Git-GitHub
An introduction to all things Git


# Git
Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. You will need a supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

You will need an account at github.com for parts of this lesson. **Create a GitHub account if you don't have one already.** Basic GitHub accounts are free. You can also get a free GitHub Pro account for education. Use your university email address to create your GitHub account, then apply for an [education discount](https://education.github.com/benefits). Please consider what personal information you'd like to reveal. For example, you may want to review these instructions for keeping your email address private provided at GitHub.

# Windows
Download the Git for Windows installer.
Run the installer and follow the steps below:
Click on "Next" four times (two times if you've previously installed Git). You don't need to change anything in the Information, location, components, and start menu screens.
Select “Use the nano editor by default” and click on “Next”.
Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
Click on "Next".
Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
Select "Use Windows' default console window" and click on "Next".
Click on "Install".
Click on "Finish".
To ensure that you can use git with RStudio:
Open RStudio.
In the menu, click on "Tools > Global Options...".
Click on "Git/SVN".
Ensure the checkbox "Enable version control interface for RStudio projects" is selected.
Under "Git executable" click on "Browse".
Navigate to the location of git.exe. This is typically located in "C:\Users\<Your-User-Name>\AppData\Local\Programs\Git\bin".
Click "Open".
Click "OK".
This will provide you with both Git and Bash in the Git Bash program.

# macOS
Video Tutorial
For OS X 10.9 and higher, install Git for Mac by downloading and running the most recent "mavericks" installer from this list. Because this installer is not signed by the developer, you may have to right click (control click) on the .pkg file, click Open, and click Open on the pop up window. After installing Git, there will not be anything in your /Applications folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available here.
To ensure that you can use git with RStudio:
Open RStudio.
In the menu, click on "Tools > Global Options...".
Click on "Git/SVN".
Ensure the checkbox "Enable version control interface for RStudio projects" is selected.
Under "Git executable" click on "Browse".
Navigate to the location of the git executable.
Click "Open".
Click "OK".

# Linux
If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run sudo apt-get install git and for Fedora run sudo dnf install git.
To ensure that you can use git with RStudio:
Open RStudio.
In the menu, click on "Tools > Global Options...".
Click on "Git/SVN".
Ensure the checkbox "Enable version control interface for RStudio projects" is selected.
Under "Git executable" click on "Browse".
Navigate to the location of the git executable. This is typically located in "/usr/bin".
Click "Open".
Click "OK".
