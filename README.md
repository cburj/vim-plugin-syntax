# VIM Plugin Syntax
Originally included as part of [VIMBIUS](https://github.com/cburj/vimbius), but has been isolated to reduce complexity and decrease plugin sizes.

## Features:
* Syntax highlighting for most DAI-specific files.

## Syntax Highlighting Support:
* Plugin Files (e.g. order.plugin)
* Source Definition Files (e.g. sdf.txt)
* ATF Test Scripts (e.g. Test_001.wiki)
* DF Alias (e.g. df_alias.txt)

## Installation with a Plugin Manager
* Add the following to your .vimrc file where you would normally install plugins: ``` Plug 'cburj/vim-plugin-syntax'```
* Save and Quit the file.
* Open a new VIM buffer and call ```:PlugInstall```
* Wait for the plugin to clone and install.

## Updating VIMBIUS with a Plugin Manager
* Open a new VIM buffer and call ```:PlugUpdate```
