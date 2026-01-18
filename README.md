## Pimp Your Terminal
show note from youtube video ->

![term.jpg](term.jpg)

##### Install ZSH
`sudo apt install zsh`
##### Set zsh as default
`chsh -s $(which zsh)`
##### in gnome terminal
> **profile custom command**

##### zsh default themes
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

edit .zshrc

ZSH_THEME="af-magic"

##### Install ohmyzsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

##### Zsh Must-Have Plugin
`git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

edit `.zshrc` to include plugins
`plugins=(git zsh-autosuggestions zsh-syntax-highlighting command-not-found)`

##### plugins include with ohmyzsh
https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins

##### Root config

copy `.zshrc` and `.oh-my-zsh` in `/root`

##### Font

https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/FiraMono/Regular/FiraMonoNerdFont-Regular.otf

Ajust the font in gnome terminal
