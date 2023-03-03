what is distributed VCS (version control system)?
    - Do not rely on a central system for a project version and all its versions

What language does git use?
    - `c`

What is Bare repo in GIT?
    - Contains info about VC and No working files
    - it doesnot contain .git folder
    - instead it has all the contents of  the .git subdirectory
    - working tree

How do you fix a broken commit?
    - git commit --amend
    - fix broken commit message

Conflict merge?
    - when two branches changes same line in a file or when a file got deleted in one branch and got edited in another

How to revert a commit?
    - do a new commit by removing unwanted changes
    - `git revert <commit id>` - making a commit to revert the previous commit

Git pull vs git fetch?
    - git pull
        - pulls new changes or updates from remote to local target repo
    - git fetch
        - pull all new commits from source and stores in a new branch in local repo
        - later do a git merge to merge these changes to target branch

git is-tree?
    - represents a tree object including the bode and name of each item and SHA-1 value of the tree

git stash?
    - want to shift branches and do someother task
    - we dont want a commit for temporary changes
    - this command will take the modification and store in a stack of unfinished changes that we can reapply at anytime

git stash apply?
    - bring back the saved changes into current work dir, after you comeback from where we stashed the changes

what work is restored when a deleted branch is recovered?
    - the files that were stashed and saved in the stash index list will be recovered back.Any untracked files will be lost

git diff
    - depicts the changes between the commits, commit and working tree etc
git status
    - shows the diff between the working tree and the index

git remote
    - CREATES   an entry in git config that specifies a name for a particular URL 

git clone
    - creates a new repo by copying an existing one located at the url

git stash drop
    - remove the last added stash item by default

How to find list of files changed during a commit?
    - git diff-tree{hash}
    - git diff-tree --no-commit-id --name-only -r {hash}

Branching strategies
    - feature
        - for feature
    - Task
        - WHICH code implements which task
    - Release
        - once a branch is ready for release , we can use it to release
        - creating this branch starts the next release cycle, no new feature will be added after this
        - only bug fixes and other release oriented tasks should go on

How to know if a branch has already been merged into the masteR?
    - git branch --merged
    - git branch --no-merged

Why is it desirable to do additional commit rather than amending an existing commit?
    - amend operation destroys the state that was previously saved in a commit
    - growth of a small commit and acquire unrelated changes

how to remove a file from git?
    - git reset filename ( exact opposite of git add command)
    - echo filename >> gitignore

fork
    - copy of complete repo
branch
    - just copies the code , but still remains in the same repo
    - individual projects in a repo
- clone
    - making a copy of the repo to a diff location

rebase
    - integrate changes from one branch to another
    - alternate to merge
    - rewrites the commit history in order to produce a straight linear succession of commits
merge
    - forked history back into the track again

reset
    - reset is used to return the entire working tree to last commit state
    - throw uncommited changes
    - changes which commit the branch head is currently pointing at
    - alters exisiting commit history
    - also to unstage a file
revert
    - creates a new commit the undoes the changes from previous commit
    - adds new history to project , doesnt modify the previous commit

Advanced level
How to squash last n commits into a single commit?
    - `git reset --soft HEAD~N && git commit`
    