Ian's Sublime Text Settings
---------------------------

This repository contains the settings that I use for Sublime Text 3. These are
the settings that work best for me and you are welcome to make use of them.

Getting Started
---------------

The easiest way to use this repository is to clone it into your projects space,
and then create a symlink replacing the real Sublime Text User Settings
directory with a pointer to the `User` subdirectory of this repo. On Mac OS X,
assuming that Sublime Text is installed at
`~/Library/Application Support/ Sublime Text 3`, this might look like:

    $ git clone https://github.com/IanLee1521/Sublime-Text-Settings ~/Sublime-Text-Settings
    $ cd "$HOME/Library/Application Support/Sublime Text 3/Packages"
    $ mv User User-backup
    $ ln -s ~/Sublime-Text-Settings/User User

License
-------

This code is released under the [MIT License](/LICENSE).
