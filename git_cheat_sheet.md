Git Cheat Sheet
===============

Statuses
--------
- staged: ready to be committed.
- unstaged: changed, not prepared for commit.
- untracked: not tracked by git (usually a new file).
- deleted: removed and waiting to be deleted from repo.

Branching
---------
- `git branch new_branch_name`: Create a Branch
- `git checkout -b new_branch_name`: Create a Branch And Switch To It
- `git branch -d branch_name`: Delete a Merged Branch
- `git branch -D branch_name`: Delete an Unmerged Branch
- `git branch`: List wll branches (the current branch will be starred).
- `git checkout branch_name`: Switch branches.
- `git merge master`: Merge current branch to master.

Committing
----------
- `git add -A`: Add (Stage) Everything to Git
- `git add '*.txt'`: Add (Stage) All Files Recursively
- `git rm foo.txt`: Stage A File Removal
- `git rm -r directory`: Stage a directory removal.
- `git reset foo.txt`: Remove From Staging
- `git checkout -- foo.txt`: Restore File To Last Commit
- `git reset --hard`: Reset To Last Commit (Leave Untracked Files)
- `git reset --hard remote/branch`: Reset To Last Commit On Remote
- `git reset --hard SHA`: Reset to a particular commit
- `git clean -df`: Delete Untracked Files
- `git commit -m "super cool commit"`: Commit Staged Files With Comment
- `git stash`: Stash uncommitted files.
- `git stash apply`: Apply stashed files.
- `git commit --amend`: Modify the previous commit.

- Misc.
    - HEAD: Pointed to most recent commit.

Pushing & Pulling
-----------------
- `git remote add origin https://github.com/try-git/try_git.git`: Add a remote repo.
- `git push -u origin master`: Push master branch to the origin remote repo.
- `git push origin --all`: Push all branches to origin remote repo.
- `git push origin --tags`: Push all tags to origin remote repo.
- `git pull origin master`: Pull commits on master branch from origin remove repo.

Diff
----
- `git diff develop:pom.xml master:pom.xml`: Diff a File Between Two Branches
- `git diff HEAD`: Compare Repository With HEAD (Last Commit)
- `git diff --staged`: Compare Staged Files With HEAD (Last Commit)

Merging
-------
- `git reset --hard HEAD`: Undo a merge

Misc.
-----
- `git log --summary`: View A Repo's History
- `git log -- foo/bar.txt`: View the entire history for a file
- `git show abc123`: Show the contents of a particular commit
