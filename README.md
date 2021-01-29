# My Ubuntu Configuration
## setup
### ubuntu
> ` $ sudo apt-get install ubuntu-restricted-extras `  
> Install gnome-tweak-tool > Keyboard > Additional Layout Options > Caps Lock behavior  
> Install exa  

### vim
> ` $ ln ~/configuration/vim/colors/lucius.vim ~/.vim/colors/ ` 
> 
> put this in ~/.vimrc
>> let $_SOURCE = "~/configuration/vim"  
>> source $_SOURCE/vimrc 
>
> Install **[vim-plug](https://github.com/junegunn/vim-plug)**  
> ` :PlugInstall `  
> Install **[YCM](https://github.com/ycm-core/YouCompleteMe#linux-64-bit)**  
> Install [**vim-instant-markdown](https://github.com/instant-markdown/vim-instant-markdown)**  


### zsh
> Install **zsh**  
> ` $ sudo chsh -s $(which zsh) $(whoami) `  
>  resource ~/.zshrc  
>  Install **[Zplug](https://github.com/zplug/zplug)**  
>  ` $ ln ~/configuration/zsh/p10k.zsh ~/.p10k.zsh `  

### tmux
> Install **tmux**  
> resource ~/.tmux.conf  
> Install **[tpm](https://github.com/tmux-plugins/tpm)**  
