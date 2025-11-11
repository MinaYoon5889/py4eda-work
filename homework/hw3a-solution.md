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
Complete this section with details from your setup:
- Repository URL: https://github.com/MinaYoon5889/py4eda-work
- Output of `git remote -v`: 
origin	https://github.com/MinaYoon5889/py4eda-work.git (fetch)
origin	https://github.com/MinaYoon5889/py4eda-work.git (push)
- The output of `git log --oneline`:
5ae06e7 (HEAD -> main, origin/main) Add hw3a solution document
dc25b1d Initial commit: Add README and .gitignore


## Questions

### Reflections

#### Question 1: Git Workflow Benefits
a) Before this assignment, I managed different versions of my work by adding "_1" at the end of the file name.
   Git is better to track the changes I've made and find the previous versions.
   Git also provides advantages such as making group work easier by not being able to overwrite on other's work and it allows to create separate branches(does not affect the main work)
b) For example, Git would be helpful when we work on the final project in this class. Even if several people work at the same time and erased something, it will be able to restore the version.

#### Question 2: Repository Organization
a) It is important to keep class_repo and my_repo separately because it prevents changing the class material.
   If I tried to put everything in one repository, I would have to spend time figuring out my own work and the course material.
b) In my future coursework or projects, I would organize multiple repositories by different categories (e.g. assignments or in-class exercises).
   My group projects will be in a shared Github repo to make it easier for everyone to work at the same time, preventing my personal work.
   Individual assginments will be in a separte repository as mentioned, and reference materials will be in another repository, where students are not able to modify.

#### Question 3: Commit Messages and History
a) Comparing the two messages, “Add hw3a solution documenting Git workflow and repository structure” is more useful because it specifically explains the changes I've made, which will be helpful when debugging.
   I might need to find this commit again to see the changes without opening every files.
b) I would decide to make a commit when I add a new visualization or vaidate data.
   A good "unit of work", for example, will be each commit focusing on one thing for better understanding or restoring the work later. For example, finishing to clean the data will be one.


### Graduate Questions

#### Question 1: The Three-Stage Model
a) Committing the README.md and  .gitignore together, and hw3a-solution.md was valuable because the first two sets up the structure of repository clearly.
If I've been lost after committing everything at once, it would not be able to see the clear history of the setup order, which makes harder to track.
b) Out of the four changes, I would commit write cod to load data, fix a typo in a comment first, and update README because they are separate completed work.
   I would wait on committing starting working on a new analysis function since it is half-finished, which means there could be changes.
   Staging helps me make decisions by clearly showing which files are able to be committed. 
c) git status helps me to figure out the status of modified, staged, and committed files. In workflow, I should use this to keep track of the progress and to figure out what to add to the next commit.

#### Question 2: Local vs. Remote Repositories
a) Git is described as a "distributed" version control system because local copy such as my_repos also has the entire history, which enables to track commits and history.
   Git enables user to have their own repository that can collaborate with others, while it is hard to track full version history Google Drive or Dropbox. 
b) It is valuable for developers because it allows to make commits or fix bugs offline. If I reconnect and git push, I can collaborate with others, work remotely, which is more felxible.
c) git clone creates local copy of a remote repository for the first time, git pull updates changes to local repository, and git push sends local commits to the remote repository.
   I can pull from class_repos because it is public asccess, but cannot push because only the owner has the access to modify.
   my_repo allows both since it is my file.

#### Question 3: Professional Portfolio
a) Before deciding what to commit, I need to check if its is completed. Then, I will include updates and fixing bugs. 
   To balance my work process, I am going to use branches for testing and polished work.
b) README for portfolio repository clearly shows about the project and my background.
   README for an open-source project shows more of installation and usage examples for others.
c) The value of bulding this portfolio during my coursework will help me track my progress and my skill development. 
   To make this portfolio valuable later, I should organized files, write down every projects I've done, and write clearer commit messages.
  
