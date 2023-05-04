# MAC

<https://www.youtube.com/watch?v=Ns_nLVfpNWQ> (Formatear)

brew install mc croc cask tree wifi-password speedtest-cli htop nmap wget tldr jq bat moc gh lcov

brew tap leoafarias/fvm
brew install fvm

echo "alias editar='mcedit'" | tee -a ~/.zshrc > /dev/null
echo "alias arbol='tree -L 1'" | tee -a ~/.zshrc > /dev/null

use open instead of kate for instance

zsh? from brew???

## zsh

<https://github.com/romkatv/dotfiles-public/tree/master/.local/share/fonts/NerdFonts> (USAR ESTA FUENTE)
git clone <https://github.com/romkatv/dotfiles-public.git>

sh -c "$(curl -fsSL <https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh>)"

git clone <https://github.com/bobthecow/git-flow-completion.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/git-flow-completion

git clone <https://github.com/zsh-users/zsh-syntax-highlighting.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

git clone <https://github.com/zsh-users/zsh-autosuggestions> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone --depth=1 <https://github.com/romkatv/powerlevel10k.git> ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

kate ~/.zshrc
ZSH_THEME="powerlevel10k/powerlevel10k"

plugins=(git git-flow-completion zsh-autosuggestions zsh-syntax-highlighting)

p10k configure (unicode to use icons)

cat file.json | jq .

Install wifi-password: brew install wifi-password
Know current wifi password: wifi-password
Copy current wifi password: wifi-password | pbcopy
Know password for an SSID (sample): wifi-password Nikhil

ssh-keygen -t ed25519-sk -C "Macbook"
tr -d '\n' < ~/.ssh/id_ed25519.pub | pbcopy

VSCODE:
Shell: install code PATH

DISCORD: cuando shares por primera vez,  better text readabillity

open .zshrc
alias ="arbol tree -L 1"
export PATH="$PATH:/Users/mal2tin/Development/flutter/bin"
export ANDROID_HOME="$HOME/Library/Android/Sdk"
export PATH="$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH"
export PATH="$PATH":"$HOME/.pub-cache/bin"

## fonts

<https://www.jetbrains.com/es-es/lp/mono/>

## firebase

curl -sL <https://firebase.tools> | bash
firebase login
firebase init

## git

git config --global user.name "mal2tin"
git config --global user.email "msmith@gnuinos.com.ar"
git config --global init.defaultBranch main
git config --global pull.rebase true
git config --global core.editor "code --wait"

<https://github.com/fwcd/brew-pkgs>
