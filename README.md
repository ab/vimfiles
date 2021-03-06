<!-- vim: set sw=2 tw=79: -->
Vim
===

Steam Locomotive
----------------

```

                        (@@) (  ) (@@) ( )  (@)  ()    @@    O     @     O
                  (   )
              (@@@@)
           (    )

         (@@@)
       ====        ________                ___________
   _D _|  |_______/        \__I_I_____===__|_________|
    |(_)---  |   H\________/ |   |        =|___ ___|      ___________
    /     |  |   H  |  |     |   |         ||_| |_||     _|          \_____A
   |      |  |   H  |__--------------------| [___] |   =|                  |
   | ________|___H__/__|_____/[][]~\_______|       |   -|                  |
   |/ |   |-----------I_____I [][] []  D   |=======|____|__________________|_
 __/ =| o |=-~~\  /~~\  /~~\  /~~\ ____Y___________|__|____________________|_
  |/-=|___|=    ||    ||    ||    |_____/~\___/          |_D__D |_D__D__D_|
   \_/      \_O=====O=====O=====O/      \_/               \_/    \_/   \_/

```

(This locomotive is courtesy of `sl`, by Toyoda Masashi.)

Included Bundles
----------------

TODO

- [TaskList](https://github.com/vim-scripts/TaskList.vim): display a list of
  occurrences of TODO, XXX, etc. in a buffer. Trigger it with <leader>t.
- [TComment](https://github.com/tomtom/tcomment_vim): toggle comments.
  Trigger it with `gc{motion}`, `gC{motion}`, or the `<c-/>` or `<leader>_`
  prefixes. See `:help tcomment`.
- [Closetag](https://github.com/abrody/closetag.vim): close HTML tags.
  Trigger it with `<c-/>` by default. I map it to `<c-/>.`, which works better
  with TComment. My fork enables easy user configuration of the map key.
- [Matchit.zip](https://github.com/vim-scripts/matchit.zip): extended %
  matching for HTML, LaTeX, and many other languages. This has been included in
  $VIMRUNTIME/macros/ for ages, but isn't enabled by default.

### Bundles in ./etc ###

- [Python-Mode](https://github.com/klen/python-mode): Nice integration with
  Python tools like PyLint and Rope. I found it too intrusive for regular use.


Managing Submodules
-------------------

### Getting Started ###

`git submodule init`
`git submodule update`

### Help Tags ###

If you find that git thinks you've modified your submodules when you create
helptags files with pathogen's `:Helptags` command, try this:

`echo doc/tags >> .git/info/exclude`

