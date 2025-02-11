        SOME OF THE GIT COMMANDS ARE

git --version
git config -l
git config --list
git status
git init
git add .
git add <file name>
git commit -m "messege"
git remote -v
git remote add origin <url/ssh link>
git branch -M main
git push origin main
git push -u origin main
git push
git remote set-url origin <url/ssh link>
ls
ls -la
git log
git log --oneline
git ls-tree <commit hash>
git show <blob>
git show <commit hash>
git show <commit id>


        GIT COMMANDS FOR BRANCH

git branch   (it lists all branches)
git branch <name>   (it creates a new branch)
git switch <name>   (it switches to <name> branch)
git switch -c <name>    (it creates and switches to <name> branch)
git checkout <name>     (it switches to <name> branch)

        GIT COMMANDS FOR MERGING

git checkout <name>     (for switching to the branchh in which you wants to mearge the branch file)

git merge <name>        (merging the <name> file to the present working branch)

        GIT COMMANDS FOR RENAME AND DELETE

git branch -m <old name> <new name>     (renaming the branch)
git branch -d <name>                    (deleting the branch)

        DIFF AND STASH

git diff    (show differench between the two commits)
git diff --staged   (show difference between last commit and staged)
git diff <c_hash1> <c_hash2>    (show difference in specific commits)

git stash   (save changes on temp location)
git stash save "name"   (stash naming)
git stash list      (shows stash list)
git stash apply     (applies the stash file)
git stash apply @stash{n}       (applies specific stash)
git stash pop       (applies changes and removes from the list)
git stash drop      (drops stash)
git stash apply @stash{n} <name>    (applies specific stash to the <name> branch)
git stash clear     (clears the stash)