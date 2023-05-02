# Corectrl Arch Fix

1. Install polkit-gnome.
```
$ yay -S polkit-gnome
```

2. Run this command before starting Corectrl.
```
$ exec /usr/lib/polkit-gnome/polkit-gnome-authentication-agent-1
```

3. Enter your password in the window.

4. Run corectrl.d
```
$ corectrl
```