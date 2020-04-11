Chris' Linux Files
===================

This repo was originally inspired by thoughtbots dotfiles repo. It provides a basic linux environment for comfort and coding.

## Docker compose files

These yaml files represent easy ways to set up some common development tools that I like to use.

* `Gitea` is a GitHub like web app that lets you have all of your own repos stored locally and have a nice visual front end. I use it primarily for mirroring and offline work.
* `Portainer` is used to manage all of my docker containers, because I don't keep all the docker param's in my head.
* `Traefik` is used as an ingress for docker so that I can use hostnames rather than IPs to communicate with my containers, such at `gitea`.

## Dotfiles, and what's in them.

A [vim](http://www.vim.org/) configuration:

* [Ctrl-P](https://github.com/kien/ctrlp.vim) for fuzzy file/buffer/tag finding.
* Set `<leader>` to a single space.
* Switch between the last two files with space-space.
* Syntax highlighting.
* Use [Ag](https://github.com/ggreer/the_silver_searcher) instead of Grep when available.
* Use [Exuberant Ctags](http://ctags.sourceforge.net/) for tab completion.
* Use [Vundle](https://github.com/gmarik/vundle) to manage plugins.

A [tmux](http://robots.thoughtbot.com/post/2641409235/a-tmux-crash-course)
configuration

A [git](http://git-scm.com/) configuration:

* Adds a `create-branch` alias to create feature branches.
* Adds a `delete-branch` alias to delete feature branches.
* Adds a `merge-branch` alias to merge feature branches into master.

Shell aliases and scripts:

* `git-churn` to show churn for the files changed in the branch.
* `replace foo bar **/*.rb` to find and replace within a given list of files.
* `tmuxdot` to attach to tmux session named the same as the current directory.

Credits
-------

This dotfiles repository is maintained by [@crueber](http://www.twitter.com/crueber)

Original dotfiles repository concept and basis taken from [ThoughtBot Dotfiles Repository](https://github.com/thoughtbot/dotfiles)
