# My Dotfiles

Just [kjellberg](https://github.com/kjellberg)'s dotfiles.

## Installation

1. Clone this repo into the ```~/Development``` directory.

    ```
    mkdir -p ~/Development && cd ~/Development && git clone https://github.com/kjellberg/dotfiles.git
    ```
2. Symlink configs

    ```
    ln -s ~/Development/dotfiles/vimrc ~/.vimrc
    ```

3. Install Homebrew

    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

4. Install plugins

    ```
    vim +PluginInstall +qall
    ```
