chrome-rdio
===========

A standalone Rdio Music Player for Linux

Chrome-Rdio is a simple set of scripts that use Google Chrome App feature to start a standalone Rdio window. It integrates nicely with your Linux Desktop using Xdotool and supports keyboard shortcuts using Xbindkeys.

# Installation

To build on Debian/Ubuntu: 

```bash
dpkg-deb --build chrome-rdio
```

Then install with:

```bash
sudo dpkg -i chrome-rdio.deb
```

# Dependencies

You will need Xbindkeys and Xdotool

```bash
sudo apt-get install xbindkeys xdotool
```

# Thanks
Nick Gauthier for the initial idea: https://gist.github.com/3056149

FairheadCreative for the Rdio SVG icon: http://fairheadcreative.com
