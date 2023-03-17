# [Nautilus](https://gitlab.gnome.org/GNOME/nautilus) - Make [Desktop](https://specifications.freedesktop.org/desktop-entry-spec/desktop-entry-spec-latest.html#introduction) File Script

A simple script to create a [desktop](https://specifications.freedesktop.org/desktop-entry-spec/desktop-entry-spec-latest.html#introduction) file for any executable in [Nautilus](https://gitlab.gnome.org/GNOME/nautilus).\
Right click any executable, go to "Scripts" and select "Make Desktop File".

Desktop files are used to launch applications from the desktop, menus, and other locations.\
They'll be stored in `~/.local/share/applications/` and will be named after the executable.

# Installation
1. Git clone _(recommended)_ or download
2. Symlink _(recommended)_ or extract to `~/.local/share/nautilus/scripts`

# Updating
If you used Git clone and symlinked the script; all you have to do is run `git pull` in the Git cloned directory to update the files.\
Otherwise, you'll have to re-download all the files and extract them to your nautilus scripts folder on each update.