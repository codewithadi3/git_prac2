This is the commands to push the code from the local to remote
1.create a repo in the github first and copy the repo url
2.**git init**
Initializes a new Git repository in your current folder.

**git add .**
Stages all files in the folder for the next commit.

**git commit -m "Initial commit"**
Commits the staged files with a message ("Initial commit").

**git remote add origin https://github.com/your-username/your-repo.git**
Links your local repository to a remote GitHub repository.

**git branch -M main**
Renames your current branch to main (the default branch name on GitHub).

**git push -u origin main**
Pushes your code to the main branch on GitHub and sets it as the default upstream branch.

------------------------------------------------------------------------------------------------------

After making any changes to the code, follow the below commands to push into the same branch
**git add .** stages your changes.
**git commit -m "Describe your changes"** commits them with a message.
**git push** uploads the changes to your remote GitHub repository.

------------------------------------------------------------------------------------------------------

if u want make the changes into the different branch
Pull the latest changes from main:
**git pull origin main**
Create and switch to a new branch:
**git checkout -b your-feature-branch**
Make your changes and stage them:
**git add .**
Commit your changes:
**git commit -m "Your changes description"**
Push your new branch to GitHub:
**git push origin your-feature-branch**
This way, your changes go to a separate branch and do not affect main.
