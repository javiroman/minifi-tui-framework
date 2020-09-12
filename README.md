MiNiFi TUI Framework
====================

This pure Java framework for creating Text User Interfaces is a
derivate work based in the original Jexer - Java Text User 
Interface library.

The idea is to adapt this awesome library for using in the parent
project MiNiFi TUI for managing Apache MiNiFi instances.


License
-------

This derivated work and Jexer are available to all under the MIT License.  See the file LICENSE
for the full license text.

Terminal Support
----------------

The table below lists terminals tested against Jexer's Xterm backend:

| Terminal       | Environment        | Mouse Click | Mouse Cursor | Images |
| -------------- | ------------------ | ----------- | ------------ | ------ |
| xterm          | X11                | yes         | yes          | yes    |
| jexer          | CLI, X11, Windows  | yes         | yes          | yes    |
| mintty         | Windows            | yes         | yes          | yes    |
| mlterm         | X11                | yes         | yes          | yes    |
| RLogin         | Windows            | yes         | yes          | yes    |
| alacritty(3)   | X11                | yes         | yes          | no     |
| gnome-terminal | X11                | yes         | yes          | no     |
| iTerm2         | Mac                | yes         | yes          | no(5)  |
| kitty(3)       | X11                | yes         | yes          | no     |
| lcxterm        | CLI, Linux console | yes         | yes          | no     |
| rxvt-unicode   | X11                | yes         | yes          | no(2)  |
| xfce4-terminal | X11                | yes         | yes          | no     |
| DomTerm(3)     | Web                | yes         | no           | yes    |
| aminal(3)      | X11                | yes         | no           | no     |
| konsole        | X11                | yes         | no           | no     |
| yakuake        | X11                | yes         | no           | no     |
| screen         | CLI                | yes(1)      | yes(1)       | no(2)  |
| tmux           | CLI                | yes(1)      | yes(1)       | no     |
| putty          | X11, Windows       | yes         | no           | no(2)  |
| qodem(3)       | CLI, Linux console | yes         | yes(4)       | no     |
| qodem-x11(3)   | X11                | yes         | no           | no     |
| wezterm        | X11, Windows       | no          | no           | yes(7) |
| yaft           | Linux console (FB) | no          | no           | yes    |
| Linux          | Linux console      | no          | no           | no(2)  |
| MacTerm        | Mac                | no          | no           | no(2)  |
| Windows Terminal(6) | Windows       | no          | no           | no(2)  |

1 - Requires mouse support from host terminal.

2 - Also fails to filter out sixel data, leaving garbage on screen.

3 - Latest in repository.

4 - Requires TERM=xterm-1003 before starting.

5 - Sixel images can crash terminal.

6 - Version 0.7.3291.0, on Windows 10.0.18362.30.  Tested against
    WSL-1 Debian instance.

7 - iTerm2 images only, but functional.


Acknowledgements
----------------

Jexer makes use of the Terminus TrueType font [made available
here](http://files.ax86.net/terminus-ttf/) .
