# dotfiles

Add this alias to your `~/.zshrc`:
```bash
alias dotfiles='/usr/bin/git --git-dir=$HOME/dotfiles.git --work-tree=$HOME'
```

At the dotfile repo run to not show untracked files
```bash
git config --local status.showUntrackedFiles no
```
