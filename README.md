# Zsh
My ZSH Config 

## Deploying nativ Arch Package [in development]

## Get dependencies
```
paru -S zsh zsh-syntax-highlighting zsh-autosuggestions
```

## Setup
Fetch zsh config:
```
wget https://raw.githubusercontent.com/cockhash/zsh/main/.zshrc -O ~/.zshrc
````
Setup Alias for powerlevel0k in $HOME/zsh/aliasrc:
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
```

Finish the conversion by changing your user in /etc/passwd to /bin/zsh instead of /bin/bash
or typing chsh $USER and entering /bin/zsh

## Install recommended Font
https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf
______________________________________________________________________________

## License :scroll:

This project is licenced under the GNU General Public License V3. For more information, visit https://www.gnu.org/licenses/gpl-3.0.en.html
