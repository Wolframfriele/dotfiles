# .dotfiles

clone repository in home, install stow, cd into dotfiles.

Then to link the dotfiles to the home directory:
```
stow .
```

and to unlink all the symlinks:
```
stow -D .
```


dependencies:
- git
- cosmic
- stow
- neovim

not included in the dotfiles:
- all off the cosmic config
