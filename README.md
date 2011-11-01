Vim
===

Included Bundles
----------------

TODO


Managing Submodules
-------------------

*Getting Started:*

`git submodule init`
`git submodule update`

If you find that git thinks you've modified your submodules when you create
helptags files with pathogen's `:Helptags` command, try this:

`echo doc/tags >> .git/info/exclude`

