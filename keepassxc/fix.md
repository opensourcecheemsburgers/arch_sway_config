# QT Platform Plugin Wayland Not Found Fix

1. Install qt5-wayland and qt6-wayland

```
# pacman -S qt5-wayland qt6-wayland
```

2. Set the `QT_QPA_PLATFORM` to wayland.

```
export QT_QPA_PLATFORM=wayland
```
