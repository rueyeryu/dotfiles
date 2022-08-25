# dotfiles

dependencies

paru -S alacritty thunar bspwm sxhkd exa feh polybar xorg-xsetroot xorg-xbacklight light pamixer picom-jonaburg-git dunst rofi flameshot ksuperkey nerd-fonts-jetbrains-mono polkit-gnome fm6000 network-manager-applet helix xfce4-power-manager betterlockscreen zsh zsh-autosuggestions zsh-syntax-highlighting oh-my-zsh-git catppuccin-gtk-theme papirus-icon-theme --needed --noconfirm

chmod -R +x ~/.local/bin
betterlockscreen -u ~/.config/bspwm/backgrounds/yourbg


sudo systemctl enable betterlockscreen@$USER.service
