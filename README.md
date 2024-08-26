# WARP_Launcher-zenity

**Cloudflare WARP launcher - notifier working with zenity, tested in Ubuntu 24.04.**

![MENU](https://github.com/Vivaracho/WARP_Launcher-zenity/blob/169d349546bd0d5fb2b8032108da60262abe0aeb/warp-menu.png)

![NOTIFICATION](https://github.com/Vivaracho/WARP_Launcher-zenity/blob/169d349546bd0d5fb2b8032108da60262abe0aeb/warp-noti.png)


***INSTALL:***


Install [Cloudflare client](https://one.one.one.one/) (skip if already installed).


Download the file [cloudflare.Warp.zenity.desktop](https://github.com/Vivaracho/WARP_Launcher-zenity/raw/main/cloudflare.Warp.zenity.desktop).


To install shortcut for all users

```
sudo desktop-file-install ./cloudflare.Warp.zenity.desktop
```


To install shortcut for a user

```
desktop-file-install ./cloudflare.Warp.zenity.desktop --dir=$HOME/.local/share/applications
```


If shorcut don't appears, refresh database

```
sudo update-desktop-database
```



***REMOVE:***


If you want to remove the shorcut for all users

```
sudo rm /usr/share/applications/cloudflare.Warp.zenity.desktop
```

If you want to remove the shorcut for a user

```
rm $HOME/.local/share/applications/cloudflare.Warp.zenity.desktop
```

