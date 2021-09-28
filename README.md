# .dotfiles

1.  Install Apple's Command Line Tools

        xcode-select --install

2.  Clone repo

        git clone [THIS_REPO]
        
3.  Install Oh-My-Zsh, and the plugins in [the zsh rc file](./.zshrc)

        sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

3.  Create symlinks with the dot files in this repo to your [HOME]

        # Manual af, but there are only two files atm
        ln -s ~/.dotfiles/[FILE_NAME] ~/[FILE_NAME]

4.  Install Homebrew, and the software listed in the Brewfile

        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

        brew bundle --file ~/.dotfiles/Brewfile
