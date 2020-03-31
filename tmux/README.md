## Basic Tmux Usage

* On the command prompt, type 

```
tmux new -s my_session
```

* Use the key sequence Ctrl-b + d to detach from the session.

* Reattach to the Tmux session by typing 

```
tmux attach-session -t my_session
```

Reload a tmux config file:

```
$ tmux source-file ~/.tmux.conf
```
