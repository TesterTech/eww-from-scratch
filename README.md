# eww-from-scratch

- move files in dot_config to .config, ```cd  dot_config/ ``` ```mv eww ~/.config``` 
- Put your username in eww.scss where it says <YOUR USERNAME> (line 1)
  - NOTE: the script expects ~/.cache/wal/colors.scss to be there, 
  this is created by Pywal so make sure to have that or remove the line! 
  - I put a colors.sccc in dot_cache/wal/ directory so you could use that temporarily.
 
# Monitors (hyprland.conf)
## See https://wiki.hyprland.org/Configuring/Monitors/
general {
    # See https://wiki.hyprland.org/Configuring/Variables/ for more
    ###
    # monitor=<name>,<resolution>,<position>,<scale>
    # - command: hyprctl monitors
    # - program: wdisplays
    ###

    #monitor=,preferred,auto,1,mirror,eDP-1
    monitor=eDP-1,1920x1080@60,auto,1
    #monitor=eDP-1,disable
    monitor=HDMI-A-2,1920x1080@60,auto,auto,mirror,eDP-1
#     monitor=HDMI-A-2,1600x1200@60,auto,auto
    #monitor=DP-1,5120x2160@50,auto,1.30
}
