# Mac setup for **Rails** development

http://blog.wyeworks.com/2012/4/13/my-osx-rails-installation-using-homebrew-and-rbenv-step-by-step/

Step 1, install Xcode.

Step 2, install osx-gcc-installer from https://github.com/kennethreitz/osx-gcc-installer

Step 3, So now you're ready to install Homebrew, by doing:

#  $ /usr/bin/ruby -e "$(/usr/bin/curl -fksSL https://raw.github.com/mxcl/homebrew/master/Library/Contributions/install_homebrew.rb)"

# Homebrew site give link with jusr "ruby" in front

$ brew install rbenv ruby-build

# add to your ~/.zshrc or ~/.bashrc 
export PATH=$HOME/.rbenv/bin:$PATH
eval "$(rbenv init -)"

##ZSH
upgrade to 5.0.2 via Homebrew and setup as in
http://stackoverflow.com/questions/12032583/what-is-the-definitive-way-to-install-upgrade-set-the-default-version-of-zsh


