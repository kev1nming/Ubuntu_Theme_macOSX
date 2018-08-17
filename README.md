# Ubuntu_Theme_macOSX 
A series files that can let your Ubuntu looks like the macOS(OSX).

## File source
### GitHub Repository
Dock: [dash-to-dock](https://github.com/micheleg/dash-to-dock) 

Themes: [Mc-OS-themes](https://github.com/paullinuxthemer/Mc-OS-themes)

Icons: [la-capitaine-icon-theme](https://github.com/keeferrourke/la-capitaine-icon-theme/) 
### Download link
Wallpapers Download link: [MacBuntu-Wallpapers](http://drive.noobslab.com/data/Mac/MacBuntu-Wallpapers.zip)

## How to apply the theme
First, install gnome-shell and gnome-tweak-tool

```shell
sudo apt install gnome-shell gnome-tweak-tool
```

Then, git clone these files (don't forget `--recursive`)

```shell
git clone --recursive https://github.com/kev1nming/Ubuntu_Theme_macOSX.git
```

Move `.icons` and `.themes` to your Home(~)

``` shell
cd Ubuntu_Theme_macOSX/
mv .icons/ .themes/ ~
```

Done! Now you can use `gnome-tweak-tool` to apply your theme and icons, and use wallpapers in `Ubuntu_Theme_macOSX/MacBuntu-Wallpapers/`

### Dock

To change the dock, please use [dash-to-dock](https://github.com/micheleg/dash-to-dock)

I like the default font, so I didn't change it.

You can use `gnome-tweak-tool` to change font and other settings.

## Effect sketch
#### My VirtualBox Desktop
![MacOS_Theme_for_Ubuntu.jpg](https://i.loli.net/2018/08/17/5b767c7325629.jpg)
