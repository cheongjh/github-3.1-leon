# Learn GIT

1. **`git init`**: This command initializes a new Git repository locally. It creates a new `.git` directory in your project, allowing you to start tracking changes.

2. **`git clone`**: This command is used to copy a repository from GitHub to your local computer. It sets up all the files from the repository and a tracking branch for you to start working immediately.

   Example:
   ```
   git clone https://github.com/user/repository.git
   ```

3. **`git add`**: This command adds files from your working directory to the staging area. It's a prep step for committing. You can add individual files or all changes at once.

   Example:
   ```
   git add filename.txt  # Adds a specific file
   git add .            # Adds all changes in the directory
   ```

4. **`git commit`**: This command records your changes to the local repository. It’s like taking a snapshot of your current project status. You typically provide a commit message to describe what changes were made.

   Example:
   ```
   git commit -m "Add a new feature"
   ```

5. **`git status`**: This command shows the status of your working directory and staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.

6. **`git push`**: This command is used to upload the content of your local repository to a remote repository. It's how you transfer commits from your local repository to a remote repo.

   Example:
   ```
   git push origin main  # Pushes changes from your local 'main' branch to the remote 'main' branch
   ```

7. **`git pull`**: This command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. It merges changes from the remote tracking branch to your current branch.

8. **`git branch`**: This command is used to manage branches in your repository. You can create, list, or delete branches.

   Example:
   ```
   git branch new-branch     # Creates a new branch called 'new-branch'
   git branch                # Lists all local branches
   ```

9. **`git checkout`**: This command is used to switch between branches or restore working tree files.

   Example:
   ```
   git checkout branch-name  # Switches to 'branch-name'
   git checkout -b new-branch  # Creates a new branch and switches to it
   ```

10. **`git merge`**: This command merges two branches together. This is typically used to bring changes from one branch into another (e.g., merging a feature branch into the main branch).

11. **`git rebase`**: Rebasing lets you move branches around, which helps you avoid unnecessary merge commits. The resulting linear history is often much easier to understand and explore.

12. **`git reflog`**: Git keeps track of updates to the tip of branches using a mechanism called reflog. This allows you to go back to changesets even though they are not referenced by any branch or tag.

12. **`git remote`**: A convenient tool for administering remote connections. Instead of passing the full URL to the fetch, pull, and push commands, it lets you use a more meaningful shortcut.

12. **`git reset`**: Undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.

12. **`git revert`**: Undoes a committed snapshot. When you discover a faulty commit, reverting is a safe and easy way to completely remove it from the code base.



# Github Authentication explanation

There are 2 methods for Github Authentication - SSH keys, HTTPS password
