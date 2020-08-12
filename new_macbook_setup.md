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
- keybindings.json for jumping 10 lines using c-j
- for press and hold j to work: https://stackoverflow.com/questions/39972335/how-do-i-press-and-hold-a-key-and-have-it-repeat-in-vscode

## brew
- setup homebrew
- brew install yarn
- brew install git-lfs
- brew install python
- brew install postgresql
- Some issue in pipenv install psycopg2. Have to export some env variables
https://github.com/pypa/pipenv/issues/3991#issuecomment-564645309
- Install vim again via homebrew because macvim uses system python I think (which is python 2.7)
- You might face this issue with running black in vim
https://github.com/psf/black/issues/1293#issuecomment-594459074
- install black and flake8 globally using brew if they are not in project pipfile

## docker
- install docker https://docs.docker.com/docker-for-mac/install/

## xcode
- sudo gem install cocoapods
- 

