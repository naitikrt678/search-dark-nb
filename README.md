<br/>
<p align="center">
  <h3 align="center">Search Dark</h3>

  <p align="center">
    A GNOME Shell 42+ Extension
    <br/>
    <br/>
  </p>
</p>

A fork of https://github.com/icedman/search-light made compatible with Gnome 50

This is a Gnome Shell extension that takes the apps search widget out of Overview. Like the macOS spotlight, or Alfred.

### Features

* Popup search box
* Colors, background, borders customization
* Blurred background
* Multi-monitor support

## Blurred background

Blurred background feature requires **imagemagick** to be installed in the system which will generate the blurred image.

### Installation

Manual Installation: 
- Clone this repo
```bash
$ git clone https://github.com/icedman/search-dark-nb
```
- Use the `Makefile` to build and install
```bash 
$ cd search-dark-nb
$ make
```

### Keybinding

Ctrl+Cmd+Space (change at the preference page)
Cmd - your Windows logo, or the command logo on mac. Linux also calls this the 'Super' key.

### Credits

Blur-My-Shell for background blurring code.
https://github.com/icedman/search-light for the entire project
