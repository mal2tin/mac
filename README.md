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

sudo softwareupdate --install-rosetta --agree-to-license

## brew

/bin/bash -c "$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh>)"

brew install bat cask croc firebase-cli gh htop jq lcov mc moc nmap node tree scrcpy speedtest-cli tldr wget wifi-password

brew install --cask android-platform-tools android-studio appcleaner avg-antivirus balenaetcher calibre dbeaver-community deepl deluge discord docker epic-games firefox flutter gimp google-chrome google-drive grammarly inkscape insomnia iterm2 java jetbrains-toolbox keycastr libreoffice mamp MonitorControl obs onlyoffice postman pycharm-ce send-to-kindle steam sweet-home3d teamviewer visual-studio-code vlc

<https://adoptium.net/es/download> (alternativa para instalar Java, usar aarch64)

brew tap leoafarias/fvm
brew install fvm
brew link --overwrite dart

brew update && brew upgrade

brew doctor

## others

hik-connect
ntfs for mac paragon
winbox with wine devel

## zsh

sh -c "$(curl -fsSL <https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh>)"

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

## examples

cat file.json | jq . (ver json desde terminal)
wifi-password | pbcopy (Know current wifi password and copy)

## vscode

Shell: install code PATH

## Discord

cuando shares por primera vez,  better text readabillity
<https://rogueamoeba.com/audiohijack/> instalar y luego borrar para que se instale el plugin ACE
que permite compartir la pantalla con audio.
En la misma web hay herramientas interesantes para audio.

## firebase

curl -sL <https://firebase.tools> | bash
firebase login
firebase init

## git / github

git config --global user.name "mal2tin"
git config --global user.email "<msmith@gnuinos.com.ar>"
git config --global init.defaultBranch main
git config --global pull.rebase true
git config --global core.editor "code --wait"

ssh-keygen -t ed25519-sk -C "Macbook"
tr -d '\n' < ~/.ssh/id_ed25519.pub | pbcopy

## fonts

<https://www.nerdfonts.com/>

<https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/Meslo.zip>
<https://www.jetbrains.com/es-es/lp/mono/>

## iTerm

agergar shortcut para aparacer/desaparecer
iTerm/Settings/key/hotekey

## .zrc

code .zshrc

export PATH="$PATH:/Users/mal2tin/Development/flutter/bin"
export ANDROID_HOME="$HOME/Library/Android/Sdk"
export PATH="$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH"
export PATH="$PATH":"$HOME/.pub-cache/bin"

## Screen

MonitorControl start and add to login
Deskpad and BetterDisplay try and decide.
