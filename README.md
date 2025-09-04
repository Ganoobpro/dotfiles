# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Yay

First, clone from this github

```
git clone https://aur.archlinux.org/yay.git
```

Then, install yay

```
cd yay
makepkg -si
```

Finally, verify that yay has been installed successfully by checking its version

```
yay --version
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/dreamsofautonomy/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
