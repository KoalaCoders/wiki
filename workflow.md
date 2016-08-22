# Workflow
* All changes should be done with pull request
* All pull request should be reviewed (at list 2 :ok: by admin)
* Criticize code, not people
* Create `feature/*` branch to add something new
* Create `fix/*` branch to fix something
* Commit message should be human-readable

## Example
```git
  // on master branch
  $ git pull origin master
  $ git checkout -b fix/layout
  $ git add .
  $ git commit -m 'Fixed footer padding'
  $ git push origin fix/layout
```
