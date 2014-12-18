## How to install Python 3 on a Mac virtualenv & flask ##
* from https://www.python.org/downloads/mac-osx/
* Download python 3.4 and install it
* pip3 install virtualenv
* pip3 install flask
## How to install VIM IDE ##
* ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* brew doctor
* brew install mercurial
* xcode-select --install
* cd ~/
* sudo rm -rf vim
* hg clone https://vim.googlecode.com/hg/ vim
* cd vim
* ./configure --with-features=huge --enable-pythoninterp
* sudo make && make install
* vim .bash_profile
* PATH= "/usr/local/bin:/Library/Frameworks/Python.framework/Versions/3.4/bin:${PATH}"
* export PATH
