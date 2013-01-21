## Vim help french translation

This repository provides the files from the [official archive](http://vim.dindinx.net/vimhelp-fr.tar.bz2) of the Vim help french translation (see [Vim website](http://vim.sourceforge.net/translations.php)).

The translation is based on Vim 6.2.017.

### Install for pathogen

Get [pathogen.vim](https://github.com/tpope/vim-pathogen) if you don't have it yet.

``` sh
cd ~/.vim/
git submodule add git://github.com/dblanchet/vim-help-fr bundle/help-fr
```

Then, in Vim:

``` vim
:call pathogen#helptags()
```

### Manual install

``` sh
cd ~/.local/src
git clone git://github.com/dblanchet/vim-help-fr.github
cp -R vim-help-fr/doc/* ~/.vim/doc/
cp -R vim-help-fr/after/syntax/help.vim ~/.vim/after/syntax/
```

Then, in Vim:

``` vim
:helptags
```

### Credits

See `README.fr` file.
