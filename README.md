# 26-06 /GIT CLI and GIT INIT REMOTE

- git pwd -check your current repository
- git mkdir folder /create a folder
- git touch README.md /create always a readme
- git init /turn the folder into a git repository 
- git remote add origin <ssh link> /the SSH repository address, e.g., git@github.com:<your-github-name>/web-challenges.git
- git remote -v /Check if the remote repository was successfully linked with the command
- A “fetch” and a “push” address should be printed to the terminal.
- do NOT nest git repositories inside each other

- git add <challenge folder name>
- Commit these challenge files with git commit -m "<message>" and add a meaningful message, e.g., “add solution for html and the web - personal website”.
- specify where you want to push to with the command git push -u origin main.


# 29-06 /GIT BRANCHES and PR COMMANDS 

- git switch -c <branchname> create a new branch and switch to it
- git switch <branchname> switch branches
- git branch list your branches
- git branch -a list all branches (local and remote)
- git branch -d <branchname> delete a branch
