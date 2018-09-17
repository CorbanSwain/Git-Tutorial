# Exercise 2 - Collaborating on a Project Through GitHub

*So I will need four volunteers for this exercise. Other can also participate.
Just be sure to copy the `ADDITION Operation Template` into the bottom of the
file. And add a new function and feature name.*

#### Prerequisites:
  * Git Installation
  * Exercise 1

## Option A - Visual Tool
1. Identify your feature: [your feature] (e.g. subtraction).
1. Point your web browser to: `https://github.com/CorbanSwain/Cool-Calculator`
1. In the top right of the project page press 'Fork'. When the forking process is finished,
   Copy the URL in your browser bar.
1. In the GitHub Desktop application top-bar press `File > Clone Repository ...`
   * Press the 'URL' tab.
   * URL: *the URL you copied* (e.g. https://github.com/YourName/Cool-Calculator)
1. Then Press 'Clone'.
1. When cloning is complete, press `Branch > New Branch`
   * Name: [your feature] (e.g. `subtraction`)
1. Navigate to the cloned repo (e.g. `Documents/GitHub/Cool-Calculator`) And open    `operations.py` in any plain text editor.
1. Following the template of the `ADDITION Operation Entry` add:
   1. Comments indicating the desired functionality.
   1. The proper implementation of your feature in the return block.
   1. A tuple of your feature's function name and your name after `sym_dict[...] =`
   * __Be sure to only modify your feature!__
   * __Example implementation for the subtraction feature:__

   ```python
   # SUBTRACTION Operation Entry ##############################

   # Desired Functionality: (- a b) = a - b

   def subtract(a, b):
      return a - b


   sym_dict['-'] = ('subtract', 'Mr. Swain')
   ############################################################
   ```

1. After you have implemented your feature, double check spelling and save `operations.py`.
   You can even try to test it out by editing the `test_str` variable in
   `calculator.py`.
1. Back in GitHub Desktop, in the 'Summary' Box type `Added [your feature] implementation`. Then press 'Commit to [your feature]'
1. Press 'Publish branch'.
1. Back in your browser window refresh the web page with your forked repository.
1. Click the Green 'Compare & pull request' button. Then press 'Create Pull Request'
   Congrats your just collaborated on an open source project!

## Option B - Command Line
1. Identify your feature: ____[your feature]____ (e.g. subtraction).
1. Point your web browser to: `https://github.com/CorbanSwain/Cool-Calculator`
1. In the top right of the project page press 'Fork'. When the forking process is finished,
   Copy the URL in your browser bar.
1. In your Terminal application type:

   ```shell
   git clone "your copied URL"
   cd Cool-Calculator
   ```

1. Then create and checkout your feature branch:

   ```shell
   git branch "your feature"
   git checkout "your feature"
   ```

1. Navigate to the cloned repo ond open `operations.py` in any plain text editor.
1. In your text editor, following the template of the `ADDITION Operation Entry` add:
   1. Comments indicating the desired functionality.
   1. The proper implementation of your feature in the return block.
   1. A tuple of your feature's function name and your name after `sym_dict[...] = `
   * __Be sure to only modify your feature!__
   * __Example implementation for the subtraction feature:__

   ```python
   # SUBTRACTION Operation Entry ##############################

   # Desired Functionality: (- a b) = a - b

   def subtract(a, b):
      return a - b


   sym_dict['-'] = ('subtract', 'Mr. Swain')
   ############################################################
   ```

1. After you have implemented your feature, double check spelling and save `operations.py`.
   You can even try to test it out by editing the `test_str` variable in
   `calculator.py`.
1. Back in the Terminal navigate (`cd`) back to the repository (if you left it) and type:

   ```shell
   git add -A
   git commit -m "added [your feature] implementation"
   git push -u origin "your feature"
   ```

1. Back in your browser window refresh the web page with your forked repository.
1. Click the Green 'Compare & pull request' button. Then press 'Create Pull Request'.
   Congrats your just collaborated on an open source project!
