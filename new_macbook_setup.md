install Chrome
install Xcode (in parallel)

## Clone dotfiles
```
git clone https://github.com/dnvarun/dotfiles
```
## Setup vim
- Copy .vimrc from dotfiles to ~/
- open vim 
- install packages

## Setup iterm2
- install iterm2
- Copy com.googlecode.iterm2.plist from dotfiles to ~/code/
- In preferences->General->Preferences, Load preferences from ~/code/
- install oh-my-zsh
- Copy varun.zsh-theme to ~/.oh-my-zsh/themes/
- Copy .zshrc and .zshenv(optional) from dotfiles to ~/. Make a backup of the local files for safety

## Setup github
- Create ssh key
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
- Add to https://github.com/settings/keys


## Vscode
- install vscode
- install vim plugin
- install chrome debugger
- keybindings.json

## brew
- setup homebrew
- brew install yarn
- brew install git-lfs
- brew install python
- brew install postgresql
- Some issue in pipenv install psycopg2. Have to export some env variables
https://github.com/pypa/pipenv/issues/3991#issuecomment-564645309

## docker
- install docker https://docs.docker.com/docker-for-mac/install/

## xcode
- sudo gem install cocoapods
- 

