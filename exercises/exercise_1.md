# Exercise 1 - Creating a Local Repository & Pushing to Github

*In this exercise you will create a new Git repository, push it up to GitHub,
and them commit & push a subsequent change.*

#### Prerequisites:
  * Git Installation

__You can choose to do the next steps by command line or with the GitHub desktop
tool.__

### Option A - Visual Tool
1. Open the GitHub Desktop application and log in to your GitHub account within
   the app.
1. In the app click `File > New Repository ...`, and add the following
   *  Name: `First-Repo`
   *  Description: `An example repo`
   *  Local Path: *default* (or choose your own)
  *  Initialize this repository with a README: `Yes`
   *  Git Ignore: `None`
   *  License: `None`
1. Then press 'Create Repository'
1. In your File navigation application find the First-Repo folder. In it should
   be a file named `readme.md`
1. Open a text editor and add `# Hello World` to the top of the readme.md file
   and then save.
1. Back in the GitHub Desktop type in the 'Summary' Block: `Editing Readme`
1. Now press 'Commit to Master.'
1. To publish your repository online press `Publish Repository`

### Option B - Command Line
1. Open the terminal application ('Terminal' for Mac and Linux, 'Git Bash' for Windows) and
1. Set your git configuration variables. By the following commands:

   ```shell
   git config --global user.name "Your Name"
   git config --global user.email "YourEmail@email.com"
   ```

1. To create the project directory and initialize a git repository type:

   ```shell
   cd ~
   mkdir First-Repo
   cd First-Repo
   git init
   ```

1. Create a readme file and open it in the nano text editor.

   ```shell
   touch readme.md
   nano readme.md
   ```

1. Add the text `# Hello World` to the file and save ('Ctrl+X', 'Y', 'Enter').
1. Type `git status` to see the files that have been changed. Notice that the
   readme file is unstaged.
1. To prepare the file for commit you must "stage" it for commiting. Type
   `git add -A` to accomplish this.
1. To commit this change type: `git commit -m "Initial commit"` Congrats! You just created your first repository.
1. Point your browser to github.com and log in to your GitHub account.
1. Click the green 'New' button with the notebook symbol to create a new repository.
   * Name: `First Repo`
   * Description: `An Example Repo`
   * Public: Yes
   * Initialize this Repository with a README: NO
1. Press 'Create Repository'
1. Copy the link in the URL bar of your browser.
1. Back in your Terminal window type:

   ```shell
   git remote add origin "your link goes here"
   git push -u origin master
   ```
