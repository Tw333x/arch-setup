- if gnome-terminal doesn't work use this command
```localectl set-locale LANG="en_US.UTF-8"
 locale-gen
 reboot```

- to enable network settings
```systemctl start NetworkManager.service
systemctl enable NetworkManager.service```

- to troubleshoot virtualbox
`sudo pacman -S virtualbox-host-modules-arch`
- installs modules
```sudo modprobe vboxdrv vboxnetadp vboxnetflt vboxpci
reboot```