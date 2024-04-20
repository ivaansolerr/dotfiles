This is a git bare reppository of my linux .files 
I configured an alias in my .zshrc to manage this reppository. Is managed exactly the same way as you
manage a normal git reppository, the only difference is that you have to write config instead
of git, that's it.

The respective alias declaration inside my .zshrc file:
alias config='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME'
