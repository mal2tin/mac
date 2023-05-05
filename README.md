# MAC

## Formatear

Prender la notebook manteniendo el boton apretado (o apreatar e inmediatamente mantener)
Options
Login
Disk Utility
Elegir Disco
Borrar grupo de volumenes
APfs
conectarse al wifi si no está
apple id /or use divice password
Reinstall

## appstore

Instalar todo lo necesario de la appstore (fijarse lo ya instalado en el pasado)

## brew

/bin/bash -c "$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh>)"

brew tap leoafarias/fvm

brew install bat cask croc fvm gh htop jq lcov mc moc nmap node tree scrcpy speedtest-cli tldr wget wifi-password

brew install --cask appcleaner avg-antivirus balenaetcher dbeaver-community deepl deluge discord docker epic-games firebase-cli firefox flutter gimp google-chrome grammarly iterm2 jetbrains-toolbox keycastr libreoffice mamp onlyoffice postman steam sweet-home3d teamviewer visual-studio-code vlc

brew update && brew upgrade
brew doctor

google drive hik-connect ntfs for mac paragon winbox with wine devel

android studio, pycham ce from jetbrains

## zsh

git clone <https://github.com/bobthecow/git-flow-completion.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/git-flow-completion

git clone <https://github.com/zsh-users/zsh-syntax-highlighting.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

git clone <https://github.com/zsh-users/zsh-autosuggestions> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone --depth=1 <https://github.com/romkatv/powerlevel10k.git> ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

kate ~/.zshrc
ZSH_THEME="powerlevel10k/powerlevel10k"

plugins=(git git-flow-completion zsh-autosuggestions zsh-syntax-highlighting)

p10k configure (unicode to use icons)

echo "alias editar='mcedit'" | tee -a ~/.zshrc > /dev/null
echo "alias dir='tree -L 1'" | tee -a ~/.zshrc > /dev/null

open .zshrc
export PATH="$PATH:/Users/mal2tin/Development/flutter/bin"
export ANDROID_HOME="$HOME/Library/Android/Sdk"
export PATH="$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH"
export PATH="$PATH":"$HOME/.pub-cache/bin"

## others

cat file.json | jq . (ver json desde terminal)
wifi-password | pbcopy (Know current wifi password and copy)

## vscode

Shell: install code PATH

## Discord

cuando shares por primera vez,  better text readabillity

## firebase

curl -sL <https://firebase.tools> | bash
firebase login
firebase init

## git / github

git config --global user.name "mal2tin"
git config --global user.email "msmith@gnuinos.com.ar"
git config --global init.defaultBranch main
git config --global pull.rebase true
git config --global core.editor "code --wait"

ssh-keygen -t ed25519-sk -C "Macbook"
tr -d '\n' < ~/.ssh/id_ed25519.pub | pbcopy

## fonts

<https://github.com/romkatv/dotfiles-public/tree/master/.local/share/fonts/NerdFonts> (USAR ESTA FUENTE)
git clone <https://github.com/romkatv/dotfiles-public.git>

<https://www.jetbrains.com/es-es/lp/mono/>

## iTerm

agergar shortcut para aparacer/desaparecer
iTerm/Settings/key/hotekey
