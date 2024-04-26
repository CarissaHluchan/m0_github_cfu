## Git Commands I know

- `git remote add origin git@github.com:USERNAME/REPO_NAME.git` This command tells the local repository to set the remote repository to this address. We refer to it as the `origin`.
- *`git branch -M main` (Reads as: FLAG M)* Configure Git to name the default branch main
- `git push -u origin main` This sends the current version of the project up to the remote repository, and sets the `main` branch as the default branch to send work up to.
- `git push` Sends committed changes to GitHub
- `git remote -v` Check your current git remote origin connection
- `git remote remove origin` remove your connection if you are connected to a remote origin that you do not have access to.
- `git remote add origin [insert SSH code here]` establish a connection. Create a new empty repository on **your** GitHub and connect it to that remote repository.
- `git clone [insert SSH code here]` Clone your copy of the repository to your local machine.
- `git add .` Add all in which ever directory you are located
- `git commit -m "Coomad statment here"`   - commit