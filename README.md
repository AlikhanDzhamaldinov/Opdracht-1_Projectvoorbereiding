One of the simple ways to add a new branch after cloning a repository is to follow these steps:

1. Create a new branch and switch to it:
   `git checkout -b <branch-name>`

2. Create a file in this branch.

3. Add the file to the staging area:
   `git add <file-name>`

4. Create a commit:
   `git commit -m "commit message"`

5. Push the branch to the remote repository and set the upstream:
   `git push -u origin <branch-name>`

After that, the changes will be pushed to GitHub. Then, in the GitHub interface, you can select your branch and assign one of the group members as a reviewer.
