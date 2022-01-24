# screen-commands

Screen or GNU Screen is a terminal multiplexer. In other words, it means that you can start a screen session and then open any number of windows (virtual terminals) inside that session. Processes running in Screen will continue to run when their window is not visible even if you get disconnected.

### list running sessions
    $ screen -ls
    
### start a screen session
    $ screen

### start a named session
    $ screen -S <session_name>

### detach from a session
    $ screen -d <session_name>
    or
    $ ctrl+a d
    
### attach to a detached session
    $ sreen -r <session_name>
    
### assess a screen that is already attached
    $ screen -rd <session_name>
    
### kill a running session
    $ screen -XS <session_name> quit
    
### terminate within a session
    $ ctrl+d
