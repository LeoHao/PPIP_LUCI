PPIP theme for LuCI (LEDE/OpenWRT)
========================================

PPIP is an alternative HTML5 theme for LuCI that has evolved from
luci-theme-bootstrap & luci-theme-material, in an attempt to bring a more
concise, clean and visually pleasing UX to LEDE/OpenWRT.

Issues & Updates
----------------

Found a bug? Please create an issue on GitHub:
    https://github.com/LeoHao/PPIP_LUCI/issues

Installation
------------

In time, ppip theme may be included upstream by the LEDE/OpenWRT crowd,
to have it always available, for now, please select an installation method
most suited for your case to get it:

### Adding PPIP theme to your own LEDE/OpenWRT Build

Edit your feeds.conf and add the following to it:

    # luci-theme-ppip
    src-git ppip git://github.com/LeoHao/PPIP_LUCI_THEME

Update your build environment and install the package:

    $ scripts/feeds update ppip
    $ scripts/feeds install luci-theme-ppip
    $ make menuconfig

Go to LuCI -> Themes, select luci-theme-ppip, exit, save and build as usual.

Enable the Theme
----------------

  * Go to System -> System -> Language and Style
  * Choose Darkmatter in the Design selectbox

License
-------

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 1
of the License, or (at your option) any later version.
