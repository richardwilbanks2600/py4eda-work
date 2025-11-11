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
Keeping everything seperate allows for others and myself to clearly see what
I have been working on in its totality. If I put everything in one place it 
would be incredibly messy and hard to follow.  
It seems beneficial to have a repository for each project. This allows easy 
tracking of everything I am/have been working on.  
Question 3: Commit Messages  
The second commit message was clearer than just 'update'. Clear messages allows
future viewers to easily tell what was changed when, and why it was changed.  
I would like all my future commits to be descriptive enough for someone familiar 
with the work to understand, but not too exhaustive for a total stranger to the 
project to fully grasp it in one commit.  
Grad Section  
Question 1: The Three-Stage Model  
Creating a README and gitignore together creates a continuity of work. This allows for 
others to see the though process of who made a repository and potentially help out 
even before the first commit.  
Commit the README changes first, then the data loading code. Wait on commiting 
the analysis function until it's finished, and then commit the comment change. This 
maintains a flow of progress that makes sense from the outside.  
Git status should be used when you have a bunch of different things to commit 
at once to help organize which order to do it in.  
Question 2: Local vs Remote Repository  
Git stores versions on both the local machine and a remote machine so you have a true backup.  
Offline commits allow developers the ability to work anytime they have power. This 
increases productivity on places like planes or public places with unsafe internet connections.  
Git clone, pull, and push are all facets of what makes git work so well. Being able 
to lock a repository for pull only is great for instruction and safety. My_repo allows both because I want it too, but 
if that changes in the future I can lock it.  
Question 3: Professional Portfolio  
When commit I am looking to show progress in small steps often and to minimize mistakes. However, I think it's valuable to 
show when you improve on old work in the beginning of projects.  
A portfolio README needs to showcase the strengths of the repo, while an open-source 
README might need to highlight weaknesses for someone else to take a crack at.  
Doing this now allows me to format all my following work the same way and have a consistent style.
