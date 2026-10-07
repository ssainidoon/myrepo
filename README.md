# keyboard shortcuts
(1) Shift + enter - to come out of comments
(2) control + enter - to run
(3) shift + control + c - for starting comments
(4) shift + control + R - for inserting section

# packages
I have noticed that installing 'usethis' package installed the following packages automatically,
but when loaded using library function, it loaded only 'usethis' package and not the other packages.
So, I have loaded those packages separately. For e.g., 'gitcreds' package for the time being.
The installed packages are usethis, gitcreds, gert, credentials, httr2, ini, desc, gh, rprojroot and whisker.

library(gitcreds) # for git credentials
gitcreds::gitcreds_set() # to set git credentials
gitcreds_get() # to check git credentials

# git commands
(1) git init - Initializes a new Git repository in the current directory.
(2) git clone <repository_url> - Clones an existing Git repository from a remote server to your local machine.
(3) git add <file> - Stages changes to be committed. You can specify individual files or use '.' to stage all changes.
(4) git commit -m "commit message" - Commits the staged changes with a descriptive message.
(5) git status - Displays the current status of the working directory and staging area, showing which files are modified, staged, or untracked.
(6) git log - Shows the commit history for the repository, including commit hashes, authors, dates, and messages.
(7) git branch - Lists all branches in the repository and indicates the current branch.
(8) git checkout <branch_name> - Switches to the specified branch in the repository.
(9) git merge <branch_name> - Merges changes from the specified branch into the current branch.
(10) git pull - Fetches and merges changes from a remote repository into the current branch.
(11) git push - Uploads local commits to a remote repository, updating it with your changes.
(12) git remote -v - Displays the remote repositories associated with the local repository, showing their URLs.
(13) git remote --verbose - Provides detailed information about the remote repositories, including their fetch and push URLs.
(14) git branch -vv --> prints info about the current branch
(15) git status --> shows the status of the current branch
(16) git remote show origin - shows the remote branches and their status; Displays detailed information about the specified remote repository, including its 
     branches and tracking information.
(17) git diff - Shows the differences between the working directory and the staging area or between commits, allowing 
    you to see what changes have been made.
(18) git fetch - Retrieves updates from a remote repository without merging them into the current branch.
(19) git reset <file> - Unstages a file, removing it from the staging area while keeping the changes in the working directory.
(20) git rm <file> - Removes a file from the working directory and stages its deletion for the next commit.
(21) pwd --> to check the current working directory

# General knowledge
PowerShell, Terminal and Command Line are synonyms.
These interface that comes with Git for Windows. These allow you to run Git commands
and perform version control tasks in a command-line environment.
Git Bash - The PowerShell of Git is known as Git Bash. It provides a Unix-like command-line 
interface for Git on Windows, allowing users to execute Git commands and scripts in a 
familiar environment.

# Processes
**1. Pull** - Pull is used to bring the data from the repository in the GitHub to RStudio or a folder in the laptop. Lets say you are working in a branch but new data (e.g. a folder) is added to the main branch in the repository in the GitHub and you want to bring that data to RStudio, then first make sure that 'main' branch is selected in the "Git" window (which is between Connections and Tutorial window). Then use 'Pull' button, which is in kind of greenish-blue colour to bring the changes down to the laptop.
**2. 
