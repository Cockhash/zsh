# Zsh
My ZSH Config 

## Deploying nativ Arch Package [in development]

## Get dependencies
```
yay -S zsh zsh-syntax-highlighting autojump zsh-autosuggestions
```

## Setup
```
touch "$HOME/.cache/zshhistory"
wget https://raw.githubusercontent.com/cockhash/zsh/main/.zshrc -O ~/.zshrc
mkdir -p "$HOME/.zsh"
#-- Setup Alias in $HOME/zsh/aliasrc
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
```

Finish the conversion by changing your user in /etc/passwd to /bin/zsh instead of /bin/bash
or typing chsh $USER and entering /bin/zsh
______________________________________________________________________________

## License :scroll:

This project is licenced under the GNU General Public License V3. For more information, visit https://www.gnu.org/licenses/gpl-3.0.en.html
