# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/Kotassu/.dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```


This whole readme and stow thing was a tutorial i followed, i'll leave the link https://www.youtube.com/watch?v=y6XCebnB9gs
