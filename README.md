#Leanring to Commit Assignment

1. Create a new directory with mkdir (new_directory).

2. Create new files using the touch command (i.e. touch index.html; touch style.css, etc).

3. Initiate git with the git init command.

4. Check the status of files in the directory using git status.

5. Add all the files to the staging area with git add ..

6. Commit the files in the staging area to the local repo with git commit -m 'Initial commit...'.

7. Create a main branch in preparation for the remote repo with git branch -M main.

8. Create a remote repo on github (or git cloud service of your choice), at github.com.

9. Add the remote repo with git remote add origin https://github.com/(user_name)/(repo_name).git.

10. Pust the files committed to the local repo to the remote with git push -u origin main.

11. Use git log to check the commit history of the local repo.

12. Use git revert -n HEAD to revert to earlier commits.

13. Rinse and repeat steps 4 - 10 (note only one main branch is necessary and after the initial push, simply git push can be used) as changes are made to the project files.

