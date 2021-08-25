# fluffy-invention
working with git commands
## Common Git Commands
- ```git status```
- ```git diff``` (shows difference between unstaged file and previous commited file
- ```git diff --staged``` (shows difference between last commited file and recently staged file)
- ```git add <file_name>``` (add file to staging within repo
- ```git mv <file_name> <new_path>``` (move file within repo or rename file) 
- ```git rm <file_name>``` (remove file from being commited/tracked)
- ```git commit -m "comment"``` (commit file to repo)
- ```git remote add <remote_name> <url>``` (add a remote to the local reposity for future pushing upstream)
- ```git checkout -- <file_name>``` (to discard changes in working directory)
- ** If file is deleted **: reuse : ```git checkout -- <file_name>``` (brings back a deleted file within the repo)
- ```git push -u <remote_name> <branch_name>``` (push repo upstream -u sets specific remote for future pushing to repo)

## Creating Branches
- `git branch <branch-name>
