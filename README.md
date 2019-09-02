# My fork of suckless terminal

This is a fork of a very simple terminal application called 
[suckless terminal](https://st.suckless.org/) (Version 0.8.1).

Here are some of the features that are added on top of st:

- Xresources support
- scrollback
- alpha (transparency) support 
- Boxdraw support
- default theme is [Gruvbox](https://github.com/morhetz/gruvbox)
- default font is [Adobe's Source Code Pro](https://github.com/adobe-fonts/source-code-pro) 
    (planning to change this to system mono font later)

Here are some useful bindings:

- Copy / paste: Shift + Ctrl + c/v
- Zoom in / out: Shift + Ctrl + k/

## Installation

So far, this is only confirmed to work on Linux-based systems.

```
make
sudo make install
```
