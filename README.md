# Git Commands
1 - git add file_name
It selects the file, and moves it to the staging area, marking it for inclusion in the next commit.

2 - git commit -m "commit message"

3 - git push origin branch_name

4 - git pull origin branch_name

5 - git fetch origin remote_branch_name:local_branch_name
It fetches remote branch locally with branch name local_branch_name

6 - git fetch origin remote_branch
It fetches the remote branch

7 - git cherry-pick commit_hash
It applies commit from other branch to current branch

8 - git push -d <remote_name> <branchname>
It deletes the remote branch. In most cases the remote_name will be origin.

9 - git branch -d <branch_name>
It deletes the local git branch. The -d option is an alias for --delete, which only deletes the branch if it has already been fully merged in its upstream branch.

10 - git branch -D <branch_name>
It deletes the local git branch. The -D option is an alias for --delete --force, which deletes the branch "irrespective of its merged status." You will receive an error if you try to delete the currently selected branch.