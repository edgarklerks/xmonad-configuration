# XMonad configuration #

Xmonad is a fully programmable tiling window manager in haskell.
This is my variant of XMonad.

It features topic spaces, which are controllable with a small home grown stack based language.
It manages several tmux instances associated with the topic spaces.
It works together with my dotfiles config.

# Installation #

compile with:

    stack install 
    cp dist/build/xmonad/xmonad xmonad

and run xmonad in an XSession.
