# tmux

tmux exit

//named session tmux new -s basic

Ctrl-b is command prefix

For Future Reference

Creating Sessions

Command Description

tmux new-session : Creates a new session without a name. Can be shortened to tmux new or simply tmux.

tmux new -s development : Creates a new session called “development.”

tmux new -s development -n editor : Creates a session named “development” and names the first window “editor.”

tmux attach -t development : Attaches to a session named “development.”

Default Commands for Sessions, Windows, and Panes

Command Description

Prefix d : Detaches from the session, leaving the session running in the background.&#x20;

Prefix : Enters Command mode.&#x20;

Prefix c: Creates a new window from within an existing tmux session. Shortcut for new-window.

Prefix n : Moves to the next window.&#x20;

Prefix p : Moves to the previous window.&#x20;

Prefix 0…9 : Selects windows by number.&#x20;

Prefix w : Displays a selectable list of windows in the current session.&#x20;

Prefix f : Searches for a window that contains the text you specify. Displays a selectable list of windows containing that text in the current session.&#x20;

Prefix , : Displays a prompt to rename a window.&#x20;

Prefix & : Closes the current window after prompting for confirmation.&#x20;

Prefix % : Divides the current window in half vertically.&#x20;

Prefix " : Divides the current window in half horizontally.&#x20;

Prefix o: Cycles through open panes.&#x20;

Prefix q : Momentarily displays pane numbers in each pane.&#x20;

Prefix x : Closes the current pane after prompting for confirmation.&#x20;

Prefix Space : Cycles through the various pane layouts.
