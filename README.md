This is shell script for vim editor configuration.
---


##Description

The script fetch corresponding vim plugins from github.com and use vundle to manage them.

+ Vundle: The vim plugins manager.
+ YouCompleteMe: A vim plugin to autocomplete the code you type.
+ Nerdtree: A vim plugin to list files.
+ vim-go: A vim plugin for golang developer.
+ rust: A vim plugin for rust developer.
+ YCM-Generator: A vim plugin to generate the python script for YouCompleteMe.

##Usage:
###Step1. fetch the code from github.com.
>git clone https://github.com/nightmeng/vim

###Step2. install vim scripts.
>cd vim
>./install

###Step3. install plugins.
Run vim in command mode, and then type :PluginInstall to install plugins.
