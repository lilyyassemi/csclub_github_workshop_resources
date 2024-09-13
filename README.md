# Welcome to the Cal Poly Humboldt CS Club Github Portfolio Workshop!

## Pre-Workshop Instructions:
### Install Visual Studio Code: https://code.visualstudio.com/Download 
- Required: Check the box that says “Register Code as an editor for supported file types” and the box that says “Add to PATH”
- Recommended: Check the boxes that add “Open with Code” to context menus
- Once open, go to settings and make sure that Git Enabled is checked

### Install Git and Git Bash
- In-Depth Instructions: https://docs.google.com/presentation/d/1rs-rPwyBQ8juj9wF6m6PLoHBoKlXVU0z/edit?usp=sharing&ouid=103962096229617255330&rtpof=true&sd=true
- When installing on Windows, make sure you check the box for Git Bash
- Use Visual Studio Code as Git’s default editor
- Open Git Bash when prompted and run the command “Git Version”
- Run the command: git config --global user.name “Firstname Lastname”
- Run the command: git config --global user.email “email”
- Reload Visual Studio in the source control panel
  
### Create a GitHub account: https://github.com/ 

## Workshop Notes:
### 01 Git Commands
- git init | Initializes a new Git repository in the current directory
- git status | Displays the state of the working directory and staging area, showing any changes to tracked files or untracked files
- git commit -m "message" | Records changes from the staging area into the repository with a descriptive message
- git add [file] or git add . | Adds changes from a specific file (or all files with git add .) to the staging area
- git clone [URL] | Copies an existing repository from GitHub to your local machine

### 02 Clone a Repository
- Step 1 | Open GitHub & Login 
- Step 2 | Click on the plus button in the top right corner and select "New Repository"
- Step 3 | Go to the repository page, click on the "Code" button and copy the URL
- Step 4 | In VS Code (make sure you are logged into your GitHub account), open the folder you would like to clone the repo into & then open a terminal
- Step 5 | In the terminal type “git clone [URL copied from step 3]” 
- Step 6 | Be sure to navigate INTO the repository (rather than staying in the local folder you placed the repository into) before you start working

### 03 Create Portfolio
- Step 1 | Ensure that you are working in the actual repository (not the local folder the repo is being stored in)
- Step 2 | Click on the source control to view any staged changes & commits
- Step 3 | Add index.html & style.css to the repo (see template), customize & save
- Step 4 | Open the terminal & type “git add .” to add the files to staged changes
- Step 5 | Commit that change with: git commit -m “added index.html and style.css”
- Step 6 | And finally push those changes to the remote repository with “git push”

### 04 Explore
- github.com
- github.blog
- docs.github.com
- skills.github.com
- https://jeffchiucp.github.io/portfolio/
- https://lindseyk.dev/
- https://rtdevcraft.com
- https://github.com/collections/github-pages-examples
- https://jekyllthemes.io/free
- https://www.markdownguide.org/basic-syntax/
- https://pydanny.blogspot.com/2011/08/github-is-my-resume.html?m=1
- https://github.com/bmorelli25/Become-A-Full-Stack-Web-Developer 






