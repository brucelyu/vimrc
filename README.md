![VIM](https://dnp4pehkvoo6n.cloudfront.net/43c5af597bd5c1a64eb1829f011c208f/as/Ultimate%20Vimrc.svg)

# The Ultimate vimrc

Forked from [here](https://github.com/amix/vimrc)


## How to install the Awesome version?
### Install for your own user only
The awesome version includes a lot of great plugins, configurations and color schemes that make Vim a lot better. To install it simply do following from your terminal:

	git clone --depth=1 git@github.com:brucelyu/vimrc.git ~/.vim_runtime
	sh ~/.vim_runtime/install_awesome_vimrc.sh
	
## My changes
I add a few more plugins:
- Add the [vimtex](https://github.com/lervag/vimtex) plugin for writing latex in vim.
The vimtex settings can be specified in the file `ftplugin/tex.vim` and `vimrcs/plugins_config.vim`.

- Add a snippet engine [ultisnips](https://github.com/SirVer/ultisnips).
Notice this plugin requires python3-supported vim, which is included by default if vim is installed using Homebrew.
User-defined snippets can be added in directory `UltiSnips/`.
Tons of snnipets have been included in the directory `sources_non_forked/vim-snippets/` of the original vimrc repository.
- Add the [simpylfold](https://github.com/tmhedberg/SimpylFold) plugin for the python code folding.
