# initcpio-sd-numlock
This repository contains an initcpio hook that enables numlock on some VTs BEFORE `cryptsetup-pre.target`. This ensures that numlock is enabled when entering a password when using a systemd-based initcpio.
To use this hook, copy `install/sd-numlock` to `/etc/initcpio/install/sd-numlock` and regenerate your initramfs.

This hook is based on the hook in [this post](https://bbs.archlinux.org/viewtopic.php?pid=2126890#p2126890).
