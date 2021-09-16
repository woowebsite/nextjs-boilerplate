# nextjs-boilerplate
Technical stack
- Nextjs
- typescript
- SWR
- Unitest: Jest, Enzyme


# Squash commit 
## Method 1: Commit was pushed, use git rebase
`
git checkout -b new_branch
git commit -m "commit 1"
git commit -m "commit 2"

git push
`
After push on server, use git rebase
`
git rebase --edit-todo
`