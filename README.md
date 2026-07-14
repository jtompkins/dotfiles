# Josh's dotfiles

This repo contains copies of my various dotfiles. They are set up as GNU Stow modules. Each top-level directory is a named module. To install, just run this command:

`stow [modulename]`

Make sure you've backed up any existing config files first. Stow will symlink the repo's file into the proper directories. If you don't have Stow installed, just run this command:

`brew install stow`
