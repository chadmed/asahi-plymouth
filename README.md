# Asahi Linux Plymouth Theme

This is a Plymouth theme for the Asahi Linux distribution for Apple Silicon Macs.
It's probably janky as hell.


## Installing
You should have Plymouth installed and hooked into your initrd.

1. Clone this repo somewhere.
2. Copy the `asahi` folder to `/usr/share/plymouth/themes/`.
3. Run `plymouth-set-default-theme -R asahi` as root.
Note that this procedure works for Arch and its forks. Adding -R
rebuilds the initrd automatically. For other distros, you will have to
figure out how to set your Plymouth theme and update the initrd yourself.


## Attributions
* The script that controls this theme was based heavily upon one written by <a href="https://github.com/jtyr/">Jiri Tyr</a> for their `plymouth-theme-arch-breeze` theme, also available under the MIT License. The password obfuscation bullet was also borrowed from here.

* The Asahi Linux logo was created by <a href="https://soundflora.tokyo/">soundflora*</a> and <a href="https://github.com/marcan/">Hector Martin</a>. It is available under the CC BY-SA 4.0 license.

* The Apple-like beachball is available for free for non-commercial use from
<a href="https://pngwing.com">PNGWing</a>.
