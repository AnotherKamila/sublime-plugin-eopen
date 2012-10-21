eopen -- `:e`-like file open
----------------------------

I can't stand those evil, slow and ugly Gtk2 file open/save dialogs. Therefore I have decided to make a terribly simple vim-like :e prompt that opens a file (the path can be absolute or relative to the currently opened file's directory). There is no tab-completion or anything fancy (yet), but unlike Gtk, it is fast. One more advantage is that you provide the filename at the beginning, so you get the filetype set (and there is no need to use the save dialog either :D).

By default the command is bound to Alt+E on Linux (and I have not added any other default keybindings, since I have no idea which keys are available on other systems :D)

Installation
============

with Package Control
--------------------

TODO

manually
--------

- `cd` to your `Packages` directory (`~/.config/sublime-text-2/Packages/` on Linux, `~/Library/Application\ Support/Sublime\ Text\ 2/Packages/` on OSX)
- clone the plugin by `git clone git://github.com/anotherkamila/sublime-plugin-eopen.git`