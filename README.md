# i3blocks-spotify
Very simple Python script to display artist name and track title on i3blocks.

Requires python-dbus library. Works on both Python 2 and Python3.

Disappears when Spotify is closed.

# Usage
```bash
# Spotify icon \uF1BC
[spotify]
label=
command=python3 /usr/share/i3blocks/spotify.py
#color=#81b71a
color=#00FF00
interval=5
```

# Controls

Mouse clicks (left/right) to go forward/backward through tracks and to pause/play with middle-click. 
