 # openSUSE Tumbleweed Post Install

## Set hostname
```hostnamectl set-hostname newhostname```

## Add Packman repositoy
* `sudo zypper ar -cfp 90 'https://ftp.gwdg.de/pub/linux/misc/packman/suse/openSUSE_Tumbleweed/' packman`
* `sudo zypper dup --from packman --allow-vendor-change`

## Media codecs
* `sudo zypper in opi`
* `opi codecs`

## Nvidia drivers
* Go to 
```https://en.opensuse.org/SDB:NVIDIA_drivers```

## Install Microsoft fonts
```sudo zypper in fetchmsttfonts```
