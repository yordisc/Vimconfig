# Vimconfig
 This is a repository with my personal vim configuration.

<Dependencies>

_Debian_
```bash
sudo apt install curl xterm ranger fzf rxvt-unicode neovim python3-pip powerline tmux python3-neovim make -yy
```

_Fedora_
```bash
sudo dnf install curl xterm ranger fzf rxvt-unicode neovim python3-pip powerline tmux python3-neovim make -yy
```

_Arch_
```bash
sudo pacman -S curl xterm ranger fzf rxvt-unicode neovim python3-pip powerline tmux python3-neovim make -yy
```

### Vimplug
```bash
			wget -P $HOME/.local/share/nvim/site/autoload/ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
			wget -P $HOME/.vim/autoload/ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### Pipenv
```bash
			pip3 install pipenv
			sudo pip install jupyter
```

### NVM/NPM
```bash
			cd $HOME
			sudo mkdir -m 755 $HOME/.nvm
			sudo mkdir -m 755 $HOME/.local/share/nvim/site/autoload/
			sudo mkdir -m 755 $HOME/.vim/autoload/
			git clone https://github.com/nvm-sh/nvm.git $HOME/.nvm
			cd $HOME
			curl -qL https://www.npmjs.com/install.sh | sh &&
			sudo npm install --global yarn &&
			sudo npm install -g n latest
			sudo npm install -g npm@latest
			sudo npm install -g live-server
			sudo npm install -g typescript
			sudo npm install -g ts-node
			sudo npm install -g tslib @types/node
			cd $HOME
```

### OpenIA
```bash
			cd $HOME
			touch .open_ai
			echo '### KEY API OPEN-IA ### export OPENAI_API_KEY=""' >> example.sh
			sudo chown -R 755 $HOME/.config/.open_ai
			cd $HOME
```

</details>

## Install Config
```bash
			cd $HOME
			git clone https://github.com/yordisc/Vimconfig
			chmod -R 775 Vimconfig/
			mv Vimconfig/vim/* $HOME
			rm -rf Vimconfig
			cd $HOME
```