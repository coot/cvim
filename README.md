cvim
====

`cvim` is a utility script (written in `python`) for [vim](http://vim.org)
editor.  It finds swap files in the current directory (or walks through
directory tree) and deletes the ones that are the same as the original file.
If they differ it uses
[recover.vim](http://www.vim.org/scripts/script.php?script_id=3068) to compare
them.  `cvim` is also included in
[recover.vim](http://www.vim.org/scripts/script.php?script_id=3068).

Options:
* `-f`: only find swap files (recursively) 
* `-r`: search current directory recursively 
* `-a`: ask also before deleting a swap file which does not differ from the file 
* `-h`: help 

Requirements
------------

You need to install `python` and [psutils](https://pypi.python.org/pypi/psutil).
