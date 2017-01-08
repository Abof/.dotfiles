# .dotfiles
Repository with all necessary configuration files including (g)vim, eclipse, bash(rc) etc.

**BTW**: `rc` suffix in `.bashrc` or `.vimrc` stands for *"run commands"*; originated somewhere in 1965 in MIT.

## .bash_aliases
File with useful aliases for shell. "Run" this file from your `.bashrc`; for example:

```sh
if [ -f ~/.bash_aliases ]; then
    . ~/.bash_aliases
fi
```

## midnight_commander
Files for configurating [Midnight Commander](https://en.wikipedia.org/wiki/Midnight_Commander) - *"free cross-platform orthodox file manager"*.

## .vimrc
Config file for [VIM](https://en.wikipedia.org/wiki/Vim_(text_editor)) - text editor program for Unix. Place this file in your home (`~`) directory for user-scope config; for global config place it in `/etc/vimrc` or `/etc/vim/vimrc`.
