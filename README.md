Vim
===

Included Bundles
----------------

TODO

- TaskList: display a list of occurrences of TODO, XXX, etc. in a buffer.
  Trigger it with <leader>t.


Managing Submodules
-------------------

*Getting Started:*

`git submodule init`
`git submodule update`

If you find that git thinks you've modified your submodules when you create
helptags files with pathogen's `:Helptags` command, try this:

`echo doc/tags >> .git/info/exclude`

