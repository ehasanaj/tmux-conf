# Tmux Config

## Setup

### Clone the package manager
```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### XDG Home
Make sure to have set the env variable `XDG_CONFIG_HOME=~/.config` , usually this is set in .bashrc or .zshrc
```sh
export XDG_CONFIG_HOME=~/.config
```

### Clone the tmux config
```sh
git clone http://github.com/ehasanaj/tmux-conf $XDG_CONFIG_HOME/tmux
```
