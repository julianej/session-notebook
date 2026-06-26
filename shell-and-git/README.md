# process to create a new remote repository.

# 1. checkout your local repository folder

cd notebook-session

# 2. Install git in Local

- git init

# 3. create sub-folder or whatever you need

mkdir css

# 4. create always a readme

touch README.md

# 5. go to gitHUB and create a new remote repository

- click on right Header Navigation the +
- choose an owner
- choose an Repository name

# 6. Copy the SSH repository address and add it as the “origin” repository to your local repository

- git remote add origin <ssh-repository-address>

# 7. Push your commit to the remote repository by using:

- git add <challenge folder name>
- git commit -m "<message>"

# 8. Push your commit to the remote repository by using:

- git push -u origin master
