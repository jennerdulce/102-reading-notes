# 102 - Day 03

## What I learned today

### **Git**
- Is NOT Github
- Stupid Content Tracker
- Tracks changes made to files or documents
- Is a VCS (Version Control System)
- Backs up work locally
- Ability to collaborate with other devs
- Repository Locally
- Better organization and less files
- Commits
  - Tracks changes
  - Leaves messages
  - Most recent Commit is called the "Head"
- Reduces rick of data loss since files. Synchronized with remote repositories
- Enables collaboration with multiple developers on a project

### Steps for using 'git'
*_ADD, COMMIT, PUSH_*
1. `git clone (link)
2. `git status`
3. `touch (filename)`
4. `git status`
5. `git add (filename)`
6. `git commit -m "text"` add a brief message of changes
7. `git push origin master`
<br> `rm -rf` or `sudo rm -r` to remove already created clone on your computer

### Github
- Creates repositories online
- Stores online on a 'cloud', while Git stores locally on a computer's hard drive
- Extra backup for your files
- Version Tracking
- Reviews changes
- Helps manage
<p>(DEV A) Push --> [Github] <-- Push (DEV B)</p>
<p>        <--Pull            Pull--></p>

### Other Notes
-.(file) are used for configuration
- 'sudo' = super user
- Create new file on repository on Github

## Reflection
Exciting new skill we learned today. I was happy to be able to figure out some 
answers to problems that I had on my own. While cloning a repo from github. I 
had already created a clone folder and wanted to start over. I was able to `rm -rf`
the folder and start from scratch. Also, I was able to get the command `code .` to work
My VisualStudio IDE was first installed on downloads when I initially did the shell command
on VS. I had moved the program to my applications folder, changing the directory.
At first the `code .` command was not working. I uninstalled and then reinstalled
the shell in the VS and `code .` worked!
