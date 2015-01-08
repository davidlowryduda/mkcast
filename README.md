# mkcast

A tool for creating GIF screencasts of a terminal, with key presses overlaid.

![](demo.gif)

Dependencies: `wmctrl`, `byzanz-record` (slightly patched `screenkey` already bundled)

Usage: ./cast WINNAME DURATION [COMMAND (optional)]

Example:

    # cast the window titled "Terminal" for 10 seconds, running the "reset"
    # command first
    ./cast Terminal 10 reset

screencast.conf format:

    {
        'timeout': 2.5,  # in seconds
        'position': 2,   # top=0, 1=middle, 2=bottom
        'size': 8,       # large=24, medium=12, small=8
        'mode': 1        # don't change this
    }

Only tested on GNOME on Ubuntu so far.
