# dotfiles
Repository for common linux tools configuration files

## Requirements

### Git

``` 
sudo apt install git 
```

### GNU Stow

```
sudo apt install stow
```

## Installation

Checkout this repository to your $HOME directory

```
$ cd ~
$ git clone https://github.com/radx64/dotfiles.git
$ cd dotfiles
```

then run `GNU Stow` to create symlinks
```
$ stow .
```
