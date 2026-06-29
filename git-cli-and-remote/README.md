# How to initialize git and connect to GitHub

- In the CLI navigate to the top level of the project folder.
- enter "pwd" - check your repository project folder
- Enter <git init> you should see something like Initialized empty Git repository in <folder  directory>.
- Create a new empty repository on GitHub. You will be given a SSH key. Copy that one.
- In the CLI enter: remote add origin <copied SSH key>.
- Check if the connection was successful by entering remote -v in the CLI.
- The response should be a (fetch) and a (push) connection.
