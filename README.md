# Change asus tuf keyboard color

  default : white (ffffff)

    red    : ff0000
    yellow : dafb2b
    green  : 12ff04
    every other color with hex

# USAGE

    kbcolor <hex color code>


# INSTALLATION (ARCH)

    sudo pacman -S asusctl
    systemctl enable --now asusd

# EXPORT PATH

    mkdir -p ~/.local/bin
    cp kbcolor ~/.local/bin/
    chmod +x ~/.local/bin/kbcolor 
    echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
