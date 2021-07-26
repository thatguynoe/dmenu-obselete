# Noe's build of dmenu

An almost vanilla build of dmenu.

## Patches and features

* [**password-4.9**](https://tools.suckless.org/dmenu/patches/password/dmenu-password-4.9.diff) hides input with the `-P` flag.

## Installation

```
git clone https://github.com/thatguynoe/dmenu
cd dmenu
sudo make install
```

## Please install `libxft-bgra`<sup>`aur`</sup>!

In order for dmenu to display color emojis, the `libxft-bgra`<sup>`aur`</sup> package must be installed---else, dmenu will crash.