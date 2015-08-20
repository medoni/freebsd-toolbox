# Maintenance
```
# fetch and install updates:
freebsd-update fetch
freebsd-update install
```

# Software
```
#Ports
portsnap fetch                          # fetch the latest portfiles
portsnap update                         # update the portfiles on disk with the previously fetched portfiles
portsnap update -p /usr/jails/basejail/usr/ports # update ports tree for jails
portupgrade -af                         # rebuild all installed packages
```

# See also

[Hukl Commands](https://github.com/hukl/freebsd-toolbox/blob/master/commands.md)