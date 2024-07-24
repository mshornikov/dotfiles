# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system:

-   Git

-   [GNU Stow](https://www.gnu.org/software/stow/)

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
git clone git@github.com/mshornikov/dotfiles.git
cd dotfiles
```

then use GNU Stow to create symlinks

```sh
stow .
```
