# Description

A fork from [https://github.com/gpakosz/.tmux.git](https://github.com/gpakosz/.tmux.git)

## Use

- prefix-key: `C-z`

### session

- `Ctrl-c`: create session
- `Ctrl-f`: find session
- `$`: rename session
- `s`: list all sessions

### window

- `,`: rename window
- `Ctrl-h`: previous window
- `Ctrl-l`: next window
- `Tab`: last window
- `c`: create new window
- `w`: list all windows
- `&`: close window

### panel

- `-`: split horizontally
- `|`: split vertically
- `hjkl`: pane move
- `!`: split panel to window
- `z`: full screen panel/return
- `x`: close panel

### other

- `m`: enable/disable mouse
- `Ctrl-d`: detached

### useful command

```shell
tmux ls
tmux attach -t <session-name>
tmux new -s <session-name>
tmux kill-session -t <session-name>
tmux kill-window -t <window-name>
tmux kill-server
```
