# Rofi-Power-Menu
A simple power menu for use with Rofi and Pywal originally built for [JaKooLit's Hyprland Dot Files](https://github.com/JaKooLit/Hyprland-Dots/)

## Screenshots
![Screenshot](https://raw.githubusercontent.com/darkeddie/Rofi-Power-Menu/master/screenshots/RofiPower.png)
![Screenshot](https://raw.githubusercontent.com/darkeddie/Rofi-Power-Menu/master/screenshots/RofiPower2.png)

## Requirements
- Rofi
- Pywal
- Swaylock
- A wallpaper changer

## Installation
- Follow the filestructure of .config to put files in the correct place
- Setup shortcut to Rofipower.sh and ensure its executable
- In your wallpaper script:
    - Pywal is called and pointed to your wallpaper
    - Also run: ln -sf "ADD PATH TO WALLPAPER HERE" "$HOME/.config/rofi/.current_wallpaper"

### Thank you to JaKooLit for inspiring me and helping with this
Check out [JaKooLit's Hyprland Dot Files](https://github.com/JaKooLit/Hyprland-Dots/)