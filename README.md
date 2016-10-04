# FAKE PROJECT
to play with git, git branches, jenkins, ...

## Experiments

* One jenkins job, to deal with multiple branches, we know where we are thanks
  to the GIT_BRANCH environment variable and so with conditional branching ...
* How jenkins react on changes related to `git rebase`, `git merge`, `git push`,
  `git push --tags`, ... How do we know where we are ?

## Event logs

2016-09-04 09:23 develop : commit / push
2016-09-04 09:24 master : merge / push
