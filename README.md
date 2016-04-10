## ncurses

This is an adapted ncurses build to fix ContinuumIO/anaconda-issues#455.

Changes:
* Apply patch for gcc 5
* Add terminfo database in `/usr/share/terminfo`
* build with `widec` support
