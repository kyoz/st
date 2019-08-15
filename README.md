st - simple (suckless) terminal (fork)
> st is a simple terminal emulator for X which sucks less.

## Patchs

- [st-alpha (0.8.2)](https://st.suckless.org/patches/alpha/) - Background opacity support
- [st-disable-bold-italic-fonts (0.8.2)](https://st.suckless.org/patches/disable_bold_italic_fonts/) - Add options to disable bold, italic
- [st-hidecursor (0.8.1)](https://st.suckless.org/patches/hidecursor/) - Hide the X cursor whenever a key is pressed...
- [purify theme](https://github.com/kyoz/purify/tree/master/st) - Make st look more vibrant xD

## Requirements

In order to build st you need:

- Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if necessary as root):

```
make clean install
```

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

## License
st's [license](./LICENSE)
