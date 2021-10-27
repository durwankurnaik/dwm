# dwm
How did I tackled usual problems

- Brightness problems : Use brightnessctl instead of xbacklight
- Screen tearing : Use intel driver option in optimus-manager-qt instead of modesetting driver and select acceleration to default, tearfree to true and DRI to 2
- Setting keyboard shortcuts : Use SXHKD and configure its file i.e sxhkdrc
- Tap to touch : This can be easily turned on by some command in the startup script at $HOME/.dwm/autostart.sh which is functional after autostart patch to DWM
- nm-apple, optimus-manager-qt and blueman-applet is used in the statusbar for quick access of those functions
- pactl is used to switch audio sources by making that switch_audio script or pulsemixer is useful in that case
