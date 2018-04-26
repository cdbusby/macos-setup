# macos-setup
Setup notes and scripts for new MacOS workstations.

## Software

*Homebrew*

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

*Node*

```
brew install node
```

*PHP*

```
brew tap homebrew/dupes
brew tap homebrew/versions
brew tap homebrew/homebrew-php

brew install php71

## To use PHP7.1 on CLI, add this to .bash_profile
export PATH="$(brew --prefix homebrew/php/php71)/bin:$PATH"
```

*Composer*

```
brew install mcrypt php71-mcrypt
brew install composer
```

*Oh My Zsh*

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Custom theme: https://github.com/cdbusby/cdbusby-zsh-theme
