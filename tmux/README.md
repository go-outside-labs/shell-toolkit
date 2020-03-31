## Basic Tmux Usage

* Starting a new (named session):

```
tmux new -s my_session
```

* Detach the session with `Ctrl-b + d`.

* List sessions with:

```
tmux ls
```

* Reattach a session:

```
tmux attach-session -t my_session
```

* Reload a tmux config file:

```
tmux source-file ~/.tmux.conf
```
