# Noe's build of dmenu

An almost vanilla build of [dmenu](https://tools.suckless.org/dmenu/). Running on commit [308fe78b83836371720c7d7eb2c3eac409f3cc16](https://git.suckless.org/dmenu/commit/308fe78b83836371720c7d7eb2c3eac409f3cc16.html).

## Patches and features

* [**border-20201112-1a13d04**](https://tools.suckless.org/dmenu/patches/border/dmenu-border-20201112-1a13d04.diff) adds a border around the dmenu window of width `n` with the `-bw n` flag.
* [**center-20200111-8cd37e1**](https://tools.suckless.org/dmenu/patches/center/dmenu-center-20200111-8cd37e1.diff) centers dmenu in the middle of the screen with the `-c` flag.
* [**grid-4.9**](https://tools.suckless.org/dmenu/patches/grid/dmenu-grid-4.9.diff) allows you to render dmenu's entries in a grid with the `-g` and `-l` flags.
    * [**gridnav-5.0**](https://tools.suckless.org/dmenu/patches/gridnav/dmenu-gridnav-5.0.diff) adds the ability to move left and right through a grid.
* [**password-5.0**](https://tools.suckless.org/dmenu/patches/password/dmenu-password-5.0.diff) hides input with the `-P` flag.

## Installation

```
git clone https://github.com/thatguynoe/dmenu
cd dmenu
sudo make install
```

## Please install `libxft-bgra`<sup>`aur`</sup>!

In order for dmenu to display color emojis, the `libxft-bgra`<sup>`aur`</sup> package must be installed---else, dmenu will crash.
