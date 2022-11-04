# zsh-atentus
Instalar dependencias
```
sudo apt install kitty zsh zsh-autosuggestions zsh-syntax-highlighting
```
Cambiar la shell a la zsh
```
usermod --shell /usr/bin/zsh usuario
```
Clonar repositorio
```
git clone https://github.com/ovekz/zsh-atentus
```
Copiar Archivos
```
cd zsh-atentus
cp -r .zshrc ~/.
cp -r kitty.conf color.ini ~/.config/kitty
```
Instalar powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```
