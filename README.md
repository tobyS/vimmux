# vimmux - VIM always in TMUX

If you are trying to get used to running your VIM inside TMUX -  e.g. for
running tests in a split pane - vimmux is for you. Aliasing vim to vimmux will
do the following:

- If no TMUX session for VIM is running, create a new one
- If a TMUX session for VIM exists, open the given file in a new VIM tab and
  attach the same session in the current shell

*Note*: vimmux is, by now, just a simply hack I try to use on my own to get
used to VIM in TMUX and VIM tabs.
