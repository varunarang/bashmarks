### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. git clone git://github.com/huyng/bashmarks.git
2. cd bashmarks
3. make install
4. source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** file

## Shell Commands

    sb <bookmark_name> - Saves the current directory as "bookmark_name"
    gb <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    pb <bookmark_name> - Prints the directory associated with "bookmark_name"
    dbm <bookmark_name> - Deletes the bookmark
    lb                 - Lists all available bookmarks

## Example Usage

    $ cd /var/www/
    $ sb webfolder
    $ cd /usr/local/lib/
    $ sb locallib
    $ lb
    $ gb web<tab>
    $ gb webfolder

## Where Bashmarks are stored

All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.
