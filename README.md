 # openSUSE Tumbleweed Post Install

## Set hostname
* `hostnamectl set-hostname newhostname`

## Add Packman repositoy
* `sudo zypper ar -cfp 90 'https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/' packman`
* `sudo zypper dup --from packman --allow-vendor-change`

## Media codecs
* `sudo zypper in opi`
* `opi codecs`

## Nvidia drivers
* Check: `https://en.opensuse.org/SDB:NVIDIA_drivers`

## Fonts

#### Microsoft fonts
* `sudo zypper in fetchmsttfonts`

#### Nerd fonts
* Download from: `https://www.nerdfonts.com/font-downloads`

Extract and move to:
* `~/.local/share/fonts/`


## What I Use on OpenSUSE?

#### Theme (GTK)
* https://github.com/lassekongo83/adw-gtk3

#### Shell
* Zsh: `sudo zypper in zsh`
* OhMyZsh: https://github.com/ohmyzsh/ohmyzsh

#### Icons
* Papirus icons theme: https://github.com/PapirusDevelopmentTeam/papirus-icon-theme
