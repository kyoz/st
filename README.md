# Kyoz's fork of the suckless terminal (st)
> [st](https://st.suckless.org/) is a simple, light weight, powerful ternimal implement for X

## Information
Base on [st-0.8.4](https://dl.suckless.org/st/st-0.8.4.tar.gz) version.

Patchs:
  - [purify theme](https://github.com/kyoz/purify) - Clean & vibrant color schemes for Vim, Terminals..
  - [alpha-0.8.2](https://st.suckless.org/patches/alpha/) - Terminal Opacity. Require X composite manager (e.g. compton, xcompmgr)
  - [anysize-0.8.1](https://st.suckless.org/patches/anysize/) - Allow st to resize to any pixel size

## Requirements

In order to build st you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if necessary as root):

```
make clean install
```

## Running

If you did not install st with make clean install, you must compile the st terminfo entry with the following command:

```
tic -sx st.info
```

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

