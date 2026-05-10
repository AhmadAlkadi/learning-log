# My Git Cheatsheet

## Daily workflow
```bash
git status          # what's changed
git diff            # show actual changes
git add <file>      # stage specific file
git add .           # stage everything
git commit -m "message" # commit staged changes
git push            # send to remote 
```

## Branhing
```
git checkout -b feature/name       # create + switch to new branch
git checkout main                  # switch to main
git branch                          # list branches
git branch -d branch-name          # delete merged branch
git merge feature/name             # merge feature into current branch
```

## Undoing
```bash
git restore <file>                # discard unstaged changes
git restore --staged <file>       # unstage but keep changes
git commit --amend -m "msg"       # fix last commit (DON'T after push!)
git reset --soft HEAD~1           # undo last commit, keep changes staged
git reset --hard HEAD~1           # NUKE last commit + changes (dangerous!)
```

## Inspection
```bash
git log --oneline                  # compact history
git log --graph --all --oneline    # visualize all branches
git show <commit-hash>             # see what a commit changed
git diff main..feature/name        # diff between branches
```

## Remotes
```bash
git remote -v                      # see remotes
git fetch                          # download remote changes (no merge)
git pull                           # fetch + merge
git push -u origin <branch>        # first push of a new branch
```

## Staching (save uncommitted work temporarily)
```bash
git stash                         # save current changes
git stash list                    # see stashes
git stash pop                     # restore most recent stash
```

## Useful aliases (one-time setup)
```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.lg "log --online --graph --all"
```
