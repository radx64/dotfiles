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

## Update

Pull new changes from git repository
```
$ cd ~/dotfiles
$ git pull
```

run `GNU Stow` again

```
$ stow .
```

> [!IMPORTANT]  
> If case of conflicts run 
> ```
> $ stow --adopt .
> ```
> which will copy inflicted files into repository, then thoses can be  cleaned up or reverted
> or remove conficted files and start `GNU Stow` again
