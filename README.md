Setting up a dev environment for rails and node js in Mac OS

# Text Editor
- Install Sublime
```
https://www.sublimetext.com/
```

- Open sublime using comand line (subl)
```
ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/usr/local/bin/subl
```

- User settings to get started
```
{
    "ensure_newline_at_eof_on_save": true,
    "folder_exclude_patterns":
    [
        ".svn",
        ".git",
        ".hg",
        "CVS",
        "node_modules",
        "bower_components",
        "coverage",
        "log",
        "tmp",
        "build","dist"
    ],
    "ignored_packages":
    [
        "Vintage"
    ],
    "rulers":
    [
        80
    ],
    "tab_size": 2,
    "translate_tabs_to_spaces": true
}
```
# Terminal 

- Install Term2
```
https://www.iterm2.com/
```

- Install zsh and oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

# Window management 
- Install spectacle
```
https://www.spectacleapp.com/
```

# Dev
- Command line tools for Xcode
```
xcode-select --install
```

- Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Node.js
- Install node.js
```
brew install nodejs
```

- Install npm
```
npm install npm -g
```

# Rails
- Install rbenv to handle your rails version
```
brew install rbenv ruby-build
```

- Install ruby (current stable 2.3.1)
```
rbenv install 2.3.1
```

# Postgress
- postgress installation
```
brew install postgresql
```

- start postgresql
```
brew services start postgresql
```

# SSh keys
- Adding your ssh key
```
ls -al ~/.ssh
ssh-keygen -t rsa -b 4096 -C faethon.milikouris@gmail.com
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```


# Optional 
- Install ImageMagic
```
brew install imagemagick
```

# Helpful Links
