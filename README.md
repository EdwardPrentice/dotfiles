# dotfiles

A simple system to bring my dotfiles with me relatively easily. Just clone the repo, and load them.

## Installation
`git clone https://github.com/EdwardPrentice/dotfiles.git`

Create a file called `.bashrc` with the contents
```
#!/bin/bash -eu

if [ -f $HOME/dotfiles/bashrc ]; then
    . $HOME/dotfiles/bashrc
fi
```

Then type `. .bashrc` on the commandline to source the `.bashrc` file you just created

## Free and open source
Feel free to copy this code, the general system and hack it to fit your needs
