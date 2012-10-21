eopen -- `:e`-like file open
----------------------------

I can't stand those evil, slow and ugly Gtk2 file open/save dialogs. Therefore I have decided to make a terribly simple vim-like :e prompt that opens a file (the path can be absolute or relative to the currently opened file's directory). There is no tab-completion or anything fancy (yet), but unlike Gtk, it is fast (and since you provide the filename at the beginning, there is no need to use the save dialog either).

Installation
============

with Package Control
--------------------

TODO

manually
--------

Head over to [the Downloads section](https://github.com/AnotherKamila/sublime-plugin-eopen/downloads), and place the plugin into the Installed Packages directory. Then restart Sublime Text.
