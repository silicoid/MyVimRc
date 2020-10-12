# MyVimRc
Based on https://vim-bootstrap.com/

To install copy the .vimrc to your $HOME
$ cp .vimrc ~/

The existence of the .vimrc should turn of compatibility mode. If it doesn't
start vim with
$ vim -N

The first time you start vim with this .vimrc you might see a bunch of erros.
Mainly because there is configs for modules that are not there yet.  Don't
worry exit out of vim after the initial install is done and then open it again.

To get a list of the installed plugins and their status:
:PlugStatus

# How to use

## Navigation

<F3> Open and close the tree navigation
<CTRL + w> (twice) will switch betwen the tree navigation and the edit window.
  
You will see the list of open buffers on the top left. To switch between buffers
:b <buffername> 
  or
:b <number> (2 is usually the navigation tree. Which means 1, 3, 4, 5 are your actual buffers

To get a list of the buffers with their numbers:
:buffers
