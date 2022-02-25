# My Dotfiles

Just [kjellberg](https://github.com/kjellberg)'s dotfiles.

## Installation

1. Clone this repo into the ```~/Development``` directory.

    ```
    mkdir -p ~/Development && cd ~/Development && git clone https://github.com/kjellberg/dotfiles.git
    ```

2. Install Homebrew & Oh-My-ZSH

    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

3. Symlink configs

    ```
    ln -s ~/Development/dotfiles/zsh/zshrc ~/.zshrc
    ln -s ~/Development/dotfiles/vim/vimrc ~/.vimrc
    ln -s ~/Development/dotfiles/zsh/themes/excid3.zsh-theme ~/.oh-my-zsh/themes/excid3.zsh-theme
    ```

4. Install plugins

    ```
    vim +PluginInstall +qall
    ```
