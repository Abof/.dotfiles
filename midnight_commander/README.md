# Configuration elements
Configuration is based on general `ini` mc file and folders where mc keeps macros or skins. It depends on you which "scope" you choose (user/global).

First of all run `mc -F` to check out configs locations; eg.
```
# User genral configuration file for mc:
/home/abof/.config/mc/ini
# Additional stuff for mc; eg. skins, macros etc.:
/home/abof/.local/share/mc/

#..where abof is your username ofc ;)
```

## Skins
First put skin in "additional stuff" config directory; eg: `/home/abof/.local/share/mc/skins/`.
Second: refer to that skin in main mc configuration file - `ini`; in right place ofc:
```
...
skin=skin-name.ini
...
``` 

