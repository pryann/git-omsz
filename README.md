# Git

## Parancsok

### config

- git config --global user.name "John Doe"
- git config --global user.email "johndoe@example.com
- git config --global core.editor "code --wait"
- git config --global --unset core.editor // remove
- git config --global diff.tool vscode
- git config --global difftool.vscode.cmd 'code --wait --diff $LOCAL $REMOTE'
- git config --global merge.tool vscode
- git config --global mergetool.vscode.cmd 'code --wait $MERGED'
- ssh-keygen -o -t rsa -C "your@email.com"

### Commits: status and log

- git status
- git log
- git log -n 5
- git log --oneline
- git log --oneline --graph

### Staging: add, commit, diff, restore

- git add <filename>
- git add .
- git commit -m "message"
- git commit -a -m "message"
- git commit --amend // utolsó commit módosítása
- git commit --amend -m "message"

- git diff // Show changes between the working tree and the index
- git diff --cached // compare changes between the working tree and the latest commit
- git diff mybranch master
- git diff HEAD -- file.txt // utolsó commithoz képest viszonyít
- git restore file.txt // utolsó állapot visszaállítása
- git restore --staged file.txt
- git restore file.txt -s e8a23549656a5e21f7c6fc6bf2dfedc81e0e4d4e

## Linkek

- [Gyakorló w3schools](https://www.w3schools.com/git/git_exercises.asp)
- [Git katas](https://github.com/eficode-academy/git-katas)
- [Git jegyzet](https://desoft.hu/downloads/git/git_v1.0.pdf)
