# WARP_Launcher-zenity

**Cloudflare WARP launcher - notifier working with zenity, tested in Ubuntu 24.04.**



***INSTALL:***


Install [Cloudflare client](https://one.one.one.one/
) (skip if already installed).


Download the file [cloudflare.Warp.zenity.desktop]().


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
