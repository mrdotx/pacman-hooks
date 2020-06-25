# pacman hooks

| name                 | comment                                               |
| :------------------- | :---------------------------------------------------- |
| 99-dashbinsh.hook    | after install or upgrade bash, relink /bin/sh to dash |
| 99-systemd-boot.hook | after upgrade systemd, update systemd-boot            |

## installation

- copy rules to folder /etc/pacman.d/hooks
