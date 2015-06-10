# [Git tutorial](https://docs.google.com/document/d/18wpMHrJAuHf3SDCYx3KR2tMpgMtqLR9y6KtsaBy0ROE/edit)

Git as a DVCS graph, commits and hashes. `git clone` test repo from https://github.com/piskvorky/tst

`git status`, `git diff`, `git commit`, commit messages. `git commit -a`. `git show`, `git log`.

Git config, command aliases (`git st`), hooks (e.g. for notifications, deployment). Config at `~/.gitconfig`. Repo config and hooks under `./.git`.

Working tree, staging, `git add -p`.

Remotes (https vs git URL), SSH key. Fetch, push, pull.

Feature branches, merges, resolving conflicts. Merge vs. rebase.

Keeping the history clean. Squashing commits, interactive rebase with `git rebase -i HEAD~N`. Dangers of forced push.

Tools: github. Pull request, comments, user/commit/repo/issue references.

Aborting merge, aborting rebase. Reset, hard reset.

Advanced: reflog, rerere.

Resources:
* https://www.atlassian.com/git/tutorials/
* http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/ 
* https://www.atlassian.com/git/tutorials/merging-vs-rebasing/the-golden-rule-of-rebasing 
