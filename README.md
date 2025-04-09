# cachyos-macbook-2014
 stuff i need to install cachyos on a 2014 macbook pro

 sudo pacman -S --needed git base-devel
 
git clone https://aur.archlinux.org/yay.git

cd yay

makepkg -si

yay -S broadcom-wl

sudo reboot
