# Git

Git is a version control system(VCS) for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for software development, but it can be used to keep track of changes in any files.

[This URL](https://git-scm.com/book/en/v2) is Pro Git Book. There is also a Korean translation. It is simple and useful manual.

Analyze the git source code when I have time. If it is difficult, I can start with the first commit state.

### stage area

This area is the place where the files waiting for commit to go.  
And the repository is the place that files complete the commit instruction.  

### diff

Finally, it provides an opportunity to check for changes to the code.

### Principle of Git 

Referece in [egoing](https://github.com/egoing/gistory).

Did not analyzed open source. using **gistory**! And find out principle!

```bash
$ pip install gistory | pip3 install gistory
$ gistory
```

| objects dir | components |
|-----|-----|
|  | file content (blob) |
|  | blob info (tree) |
|  | (commit) |

working directory - index, staging area, cache - repository

### stash

Use it that something you want to hide. more info in man pages. It can not apply Untracked files..

### relation to git reset

working directory | index | repository
----|----|----
working tree | staging area | history
working copy | cache | tree
  |  |git reset --soft
  | git reset --mixed | "  
git reset --hard | " | "

