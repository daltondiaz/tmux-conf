# My environment configs

## Tmux

To use tmux configurations create a symbolic link to:

`ln -s /home/your_home_dir/personal-confs/tmux-conf/tmux.conf /home/your_home_dir/.tmux.conf`

### Tmux Plugin Manager 

You need to install the tpm 
[github tpm](https://github.com/tmux-plugins/tpm)

Apply the configuration sourcing the .tmux.conf:

 ```tmux source ~/.tmux.conf```

## i3-wm

[i3-config](https://github.com/daltondiaz/i3-config)


## Neovim

[Neovim configs](https://github.com/daltondiaz/init.lua)

## Go Lang

- [Download golang.org](https://go.dev/dl/)
- [Installation instructions](https://go.dev/doc/install)

Move the go directory to ```/usr/local``` directory ```sudo mv go /usr/local```, add global variable to your shell (zsh) `nvim ~/.zshrc`

Past end of file:

```sh
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```
Update the shell `source ~/.zshrc`
