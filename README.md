# .config

Sway requires additional setup for privilege escalation. Without this setup,
sway will fail to start with session activation permission failures. Choose one
of the two available options (In alphabetical, not recommended, order):

1. polkit: This will make sway "just work" right after installation but may be
           a weightier solution than desired.

2. seatd: Already required as a sway dependency, this is a lighter-weight
          solution but requires some user configuration: Enabling the service,
          adding your user to the "seat" group, then logging out/in again.

Either option should provide the same functionality/stability. Refer to the
Sway wiki page for information.
Optional dependencies for sway
    bemenu: Wayland-native alternative to dmenu
    dmenu: Application launcher used in default config
    foot: Terminal emulator used in the default configuration
    i3status: Status line generation
    mako: Lightweight notification daemon
    polkit: System privilege control. Required if not using seatd service [installed]
    swaybg: Wallpaper tool for sway
    swayidle: Idle management daemon
    swaylock: Screen locker
    waybar: Highly customizable bar
    xorg-xwayland: X11 support
