# tmux-config
## Prerequisites
1. Patched font.
## How to setup?
1. Install [`tmux`](https://github.com/tmux/tmux)
1. Make sure `XDG_CONFIG_HOME` environment variable is set (typically to `$HOME/.config`) e.g. in shell rc:
    ```bash
    export XDG_CONFIG_HOME="$HOME/.config"
    ```
1. Install [`tmux plugin manager`](https://github.com/tmux-plugins/tpm)
1. Create `$XDG_CONFIG_HOME/tmux` directory and clone repo there:
    ```bash
    mkdir -p $XDG_CONFIG_HOME/tmux && \
    cd $XDG_CONFIG_HOME/tmux && \
    git clone https://github.com/skomposzczet/tmux-config .
    ```
1. Reopen tmux or execute command:
    ```bash
    tmux source $XDG_CONFIG_HOME/tmux/tmux.conf
    ```
