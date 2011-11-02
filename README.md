Vim
===

Train
-----

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

Included Bundles
----------------

TODO

- [TaskList](https://github.com/vim-scripts/TaskList.vim): display a list of
  occurrences of TODO, XXX, etc. in a buffer. Trigger it with <leader>t.
- [Python-Mode](https://github.com/klen/python-mode): Nice integration with
  Python tools like PyLint and Rope.


Managing Submodules
-------------------

*Getting Started:*

`git submodule init`
`git submodule update`

If you find that git thinks you've modified your submodules when you create
helptags files with pathogen's `:Helptags` command, try this:

`echo doc/tags >> .git/info/exclude`

