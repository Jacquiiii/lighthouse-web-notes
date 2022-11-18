## Day 2 Lecture Notes: Nov 15, 2022

* Tools:
    * VS code:
        * Learn keyboard shortcuts
        * Add colours to vs code for curly braces lines
        * Option + Z for word wrap
        * To move text in VS code: Highlight line, hold ALT and arrow
    * Don’t use or install Copilot in bootcamp
    * Google searches
* Git:
    * Git remote -v: check if file is linked to a git repo
    * Git pull:
    * Git log: shows list of commits
    * Git branch: check branch
    * Create a repo:
        * Go to git hub, click new, add name/description, leave the rest as is, then create repo
        * Copy ssh link
        * Create folder in terminal via mkdir, cd into it, then add document via touch
        * Git remote add origin + ssh link
        * Git branch -M main (rename master branch to main)
        * Git push -u origin main (shortcut so you don’t need to do git push origin main each time but rather just do git push)
    * Adding to repo:
        * Git add .
        * Git commit -m “add comment”
        * Git push
    * Ls -al in the folder to see if it’s being tracked by git, will see a .git file
* Incremental Development:
    * State hypothesis
    * Verify Hypothesis
    * Focus on core problem then focus on edge cases (the what ifs)
    * Test after every step with a console.log
        * Tips: 
            * Typeof in console.log to check if something is a string or number etc.
            * Be intentional with what you use. Number() would be more readable than + for example.
* Javascript:
    * Process.exit() to stop a process instead of using break
    * Don’t always need to use an else, can use console.log etc instead.

### Links

* [Code demo](https://github.com/DominicTremblay/w1d2-west-telus-nov14)
* [Lecture recording](https://vimeo.com/771314762/1ee5c7dbce)