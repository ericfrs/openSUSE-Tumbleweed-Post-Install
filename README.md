 # openSUSE Tumbleweed Post Install

## Set hostname
* `hostnamectl set-hostname newhostname`

## Add Packman repositoy
* `sudo zypper ar -cfp 90 'https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/' packman`
* `sudo zypper dup --from packman --allow-vendor-change`

## Media codecs
* `sudo zypper install opi`
* `opi codecs`

## Nvidia drivers
* [Nvidia openSUSE article](https://en.opensuse.org/SDB:NVIDIA_drivers)

## Fonts

### Microsoft fonts
* `sudo zypper install fetchmsttfonts`

### Nerd fonts
* Download from [NerdFonts](https://www.nerdfonts.com/font-downloads)
* Extract and move to: `~/.local/share/fonts/`


## What I Use on OpenSUSE?

### Theme (Gnome)
* https://github.com/lassekongo83/adw-gtk3

### Shell

#### Starship
* `sudo zypper install starship`
* `echo 'eval "$(starship init bash)"' >> ~/.bashrc`
* [Starship Guide](https://starship.rs/guide/)

### Icons
* Papirus icons theme: https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

### Wallpapers
* [Ömer Duran Gumroard](https://omerduran.gumroad.com/) 
