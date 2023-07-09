# -github-3.1-SimonOng-

[![N|Solid](https://github.com/ioctlsg/-github-3.1-SimonOng-/blob/main/images.png)](https://github.com/ioctlsg/-github-3.1-SimonOng-)


1. `git clone`: This command is used to create a copy of a remote Git repository on your local machine. It downloads the entire repository, including all its branches, files, and commit history. The basic syntax for cloning a repository is `git clone <repository_url>`. For example, if you wanted to clone a repository with the URL `https://github.com/example/repo.git`, you would run `git clone https://github.com/example/repo.git`.

2. `git add .`: This command is used to stage changes in your working directory for the next commit. The dot (`.`) represents the current directory, and it tells Git to add all modified and new files in the current directory and its subdirectories. You can also specify individual files or directories instead of using the dot. For example, `git add file.txt` would only add the `file.txt` file. After running `git add`, the changes are ready to be committed.

3. `git commit -m "message"`: This command is used to create a new commit with the changes you have staged. The `-m` option allows you to specify a commit message that describes the changes made in the commit. The commit message should be concise but informative. For example, `git commit -m "Add feature XYZ"` would create a commit with the message "Add feature XYZ".

4. `git push`: This command is used to upload your local commits to a remote repository. It updates the remote repository with the latest changes from your local branch. The basic syntax for pushing commits is `git push <remote> <branch>`. For example, `git push origin main` would push the commits from your local `main` branch to the `origin` remote repository. This command requires appropriate access and authentication to the remote repository.

Overall, these commands are essential for collaborating with Git and GitHub. `git clone` allows you to download a remote repository, `git add` stages your changes, `git commit` creates a new commit, and `git push` uploads your local commits to a remote repository.