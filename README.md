# pacman-hooks

| name                 | comment                                               |
| :------------------- | :---------------------------------------------------- |
| 99-dashbinsh.hook    | after install or upgrade bash, relink /bin/sh to dash |
| 99-systemd-boot.hook | after upgrade systemd, update systemd-boot            |
| 99-ventoy.hook       | after install or upgrade ventoy, set shebang to bash  |

## installation

- copy rules to folder /etc/pacman.d/hooks
