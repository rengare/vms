add to `/etc/X11/xorg.conf.d/10-serverflags.conf`

```
# 10-serverflags.conf
Section "ServerFlags"
        Option "AutoAddGPU" "off"
EndSection

```
