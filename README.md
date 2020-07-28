# .dotfiles
## tsujin's Tome of Linux Wizardry

Installation steps:

1) Set config alias with: `alias config='alias config='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'`
2) To prevent recursion issues: `echo ".dotfiles" >> .gitignore` 
3) Clone the repo: `git clone --bare https://github.com/tsujin/.dotfiles $HOME`
4) Then checkout with `config checkout`
