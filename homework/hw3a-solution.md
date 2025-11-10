# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.
### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
- Repository URL: https://github.com/richardwilbanks2600/py4eda-work
- Output of `git remote -v`:  
origin  https://github.com/richardwilbanks2600/py4eda-work.git (fetch)  
origin  https://github.com/richardwilbanks2600/py4eda-work.git (push)
- The output of `git log --oneline`:  
be8a510 (HEAD -> main, origin/main) Add hw3a solution document  
d9fa67d Initial commit: Add README and .gitignore
## Part 4: Questions
Questions answered after creating this repository:
### Reflections
Question 1: Git Workflow Benefits  
Prior to completing this assignment I would save different versions of work 
either in a Box folder or locally with version specific names in parentheses. 
This is in contrast to Git which is faster, more easily shared with others,
and provides a better picture of what changes were made to work and when those
changes were made.  
Git's commit history would have been invaluable when I was doing
my senior capstone project. At one point our team lost our report
documentation, but having Git would have made version control and
collaboration much easier.  
Question 2: Repository Organization  

