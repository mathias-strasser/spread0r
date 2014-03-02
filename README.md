gritz
=====

gritz is a txt reader, which makes you reading twice as fast as usual


Installation
============

gritz should run on all platforms supporting perl and gtk2-perl. 
Just clone into the github repo or download a snapshot of:
[gritz github repo](https://github.com/xypiie/gritz)

After installing perl and gtk2-perl you can start it by double clicking
gritz.pl or running it in terminal like:

`./gritz.pl`

Dependencies on ArchLinux
-------------------------
`pacman -S gtk2-perl`

Dependencies on OSX
-------------------
### Preparation:
  * Install and setup X11
  * Install and setup Homebrew

### Setup
1. Install glib/Pango/Gtk2 with Homebrew
  * brew install glib pango gtk+
2. Add X11 Package Config Path to bashrc
  * add: export PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/opt/X11/lib/pkgconfig
2. Local Perl CPAN Setup
  * perl -MCPAN -e shell
  * follow setup
  * $ echo '[ $SHLVL -eq 1 ] && eval "$(perl -I$HOME/foo/lib/perl5 -Mlocal::lib=$HOME/foo)"' >>~/.bashrc
3. Install Perl modules
  * perl -MCPAN -e shell
  * perl> install Glib
  * perl> install Cairo
  * perl> install Pango
  * perl> install Gtk2
3. have fun with gritz

Dependencies on Windows
-----------------------
TODO
