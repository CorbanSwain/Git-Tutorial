# Git Tutorial: Presentation Outline

## Slides - Motivation for a Version Controlled Workflow and GitHub - [10 min]

*Overview: Through the next few slides, I hope to motivate the use of version
control in general and show some examples of Git and GitHub being utilized
in practice with my own projects.*

1. The general coding workflow:
   *  map out project on paper
   *  Search via stack exchange and other online resources to identify solutions
   *  Try various implementations for reaching a goal. Until you narrow in on a
      good method.
   *  Use comments to explain how to use your code (for your self and others)
   *  Difficult to locate old versions or manual versioning with file names:      
      (e.g. `compute_1.1`, `compute_1.2`). (Dont know whats diff between versions)
   *  Working on multiple computers can prove very difficult even if the code is in the   
      cloud. Directory names are different, line endings get messed up.
   *  Dropbox or Google Drive (potentially email) for sharing code with other people.
   *  Large overhead to test and code on a computing cluster, possible with FTP, rsync, etc.
   *  Troubleshooting exactly what changes created a new bug often rely on memory or
      copies of previous saves, or manually changing pecieces of code back.
   *  Ususally only one working version of the code.
   *  Keep track of projects problems and goals
1. The Version Controlled Workflow with GitHub
   *  Con - Saving of the file itself alongside commits to a local and remote repository.
   *  Simultaneous collaboration with as many people as desired
   *  Sharing of software for release with
   *  Published ReadMe to explain the purpose for your code and instructions for
      it's use.
   *  Issue tracking with builtin tools
1. What is Git
   *  "Git is a distributed version control system"
   *  Basically everywhere that there is a copy of your project, the entire
      change history and in-progress parts are stored as well.
1. What is GitHub
1. Consolidation Example - MATLAB Utilities
   * __Git is a framework where copy-pasting is obsolete.__
1. Collaboration Example - Seaborn Pull Request
   * __GitHub is the forum where code is improved.__
   * Not only did this solve a problem for me, but there is now a public
     version of the Seaborn software with this feature which anyone can use at
     any time.
1. Released Software Example - Volume Point Picker
   * __GitHub is the platform for software to be released.__
   * See issue tracker
1. Yes this is a lot, but the Energy Barrier is low.
   * You could just throw all your code in a folder and commit once a day,
     just for the versioned backups.
   * Quick and dirty example: Put existing project on GitHub, then update.
     1. `$ cd to/my/project/`
     1. `$ git init`
     1. `$ git add -A`
     1. `$ git commit -m "initial commit of existing proj."`
     1. `$ git remote add origin http://github.com/CorbanSwain/Example-Proj`
     1. `$ git push -u origin master`
     1. `$ emacs test.py` *... edit file ... save file.*
     1. `$ git add -A`
     1. `$ git commit -m "Added feature to test"`
     1. `$ git push`


## Slides - More Complex (But Important) Topics
* Managing code alongside large files
* Merging conflicting commits
