vim-showinvisibles
==================

Visualizing invisible characters (white space and tab) in Vim

This is a fork from the original [cream-showinvisibles.vim](http://vim.sourceforge.net/scripts/script.php?script_id=363). It added the following enhancement:

1. added support to visualize the space character(0x20)

2. use gray color when visualization is on, restore to default color when visualization in off

Usage
=====

1. Patch your vim sourcecode [patchsource](https://groups.google.com/forum/?fromgroups=#!topic/vim_dev/dIQHjW1g92s). if you are too lazy to compile you can use [a binary version already patched](https://github.com/michalliu/gvimim/tree/master/vim73)

2. Copy `cream-showinvisibles.vim` to your vim plugin folder

3. The magic key is `<F6>`

Contributors
============

1. [Steve Hall](http://vim.sourceforge.net/scripts/script.php?script_id=363) the original plugin author

2. [Arkanosis](https://groups.google.com/forum/?fromgroups=#!topic/vim_dev/dIQHjW1g92s) the patch author