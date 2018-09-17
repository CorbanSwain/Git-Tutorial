# Getting started with Git and GitHub

## Creating A GitHub Account
*You'll need a GitHub account to use Git most effectively, if you already have
an account, great! You can skip this step.*

1. Point your web browser to [github.com/join](https://github.com/join).
1. Enter your information and follow the on-screen steps to create an account.

## Local Installations

I'll be asking you to install both a command line tool __and__ a visual tool for
working with Git on your computer. Below are instructions for
[Windows](#Windows), [Macintosh](#Macintosh), and [Linux](#Linux).
operating systems.

### Windows

#### Git Bash - Command Line Tool

1. Point your web browser to [git-scm.com/download/win](https://git-scm.com/download/win)
1. Open the `.exe` download and follow the on screen instructions for getting things set up.
1. Once in install is complete, find the program named "Git Bash" and run it.
You should see a termainal window. Type `git --version` to ensure the
installation was successful. If the installation succeeded a version number should be displayed.

#### GitHub Desktop - Visual Tool

1. Point your web browser to [desktop.github.com](https://desktop.github.com/).
1. Download GitHub Desktop and open the windows installer. Follow these [instructions for instalation](https://help.github.com/desktop/guides/getting-started-with-github-desktop/installing-github-desktop/#platform-windows).

### Macintosh

#### Git - Command Line tool

*Your mac is a Unix-based operating system so you may already have Git
installed, otherwise you'll need to install "Command line Tools for Xcode"
to get it running.*

##### Testing for Git
Open your Terminal application and type `git --version`, then press Enter. If
you see something like this

```shell
$ git --version
git version 2.15.2 (Apple Git-101.1)
```

... then git is already installed. You can stop here.

##### Installing Command Line Tools for Xcode

*The following should be roughly similar to the instructions you see in the
terminal window after typing `git --version`. Feel free to follow those
instructions if they are more clear.*

1. Open your Terminal application and type `xcode-select --install` the press
   enter.
   * __If that doesn't work__, point your browser to the
   [Apple Developer Login Page](https://idmsa.apple.com/IDMSWebAuth/login?appIdKey=891bd3417a7776362562d2197f89480a8547b108fd934911bcbea0110d07f757&path=%2Fdownload%2Fmore%2F&rv=1)
   and sign in with your [Apple ID](https://support.apple.com/en-us/HT204316).
   Follow the on-screen instructions until you reach a list of downloads.
   * There, you should download "Command Line Tools (macOS [your macOS version])
     for Xcode". Search through the list and try not to download a "Beta" version
     unless you have to.
     * To figure out your macOS version click the Apple symbol in the top left
       of your computer then click "About this Mac." The macOS version number
       should be listed (e.g. 10.13.4) in the dialog that appears.
     * You only need the first two numbers (e.g. 10.13) to match to the package
       in the downloads list.
   * Download a `.dmg` file of the proper Command Line Tools version. Open the
     `.dmg` then double click on the `.pkg` file contained within.
1. Follow the on-screen instructions until the installation in complete.
1. Test your installation by running `git --version` in your Terminal
   application. If the installation succeeded a version number should be displayed.

#### GitHub Desktop - Visual tool

1. Point your web browser to [desktop.github.com](https://desktop.github.com/).
1. Download GitHub Desktop and open the `.dmg` file. Follow these [instructions for instalation](https://help.github.com/desktop/guides/getting-started-with-github-desktop/installing-github-desktop/#platform-mac).

### Linux

#### Git - Command Line tool
*Adapted from
[@derhuerst](https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-linux-md)*

1. Determine which Linux distribution your system is based on. See
[this list](http://en.wikipedia.org/wiki/List_of_Linux_distributions) for reference.
**Most Linux systems--including Ubuntu--are Debian-based**.

   1. Debian-based Linux systems: copy and paste the following into your
      terminal Window then press Enter.

      ```shell
      sudo apt-get update
      sudo apt-get upgrade
      sudo apt-get install git
      ```

   1. Red Hat-based Linux systems: copy and paste the following into your
      terminal Window then press Enter.

      ```shell
      sudo yum upgrade
      sudo yum install git
      ```

1. Test your installation by running `git --version` in your Terminal
   application. If the installation succeeded a version number should be displayed.

#### Git Extensions - Visual Tool
*I haven't actually used a visual tool on Linux, and GitHub Desktop is [still
in development](https://github.com/desktop/desktop/issues/1525) for such operating systems.
See a full list of visual tools for Linux
[here](https://git-scm.com/download/gui/linux)*

1. Follow the instructions found at the [Git Extensions Webpage](https://gitextensions.github.io/).
