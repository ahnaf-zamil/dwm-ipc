# Custom DWM-IPC Build

This is my custom [DWM](dwm.suckless.org/)(IPC) build with custom patches and Polybar support. 

## FAQ

- Why did I use IPC? Because I wanted to use Polybar since it's a pain to customize the normal DWM bar.

- Did I change any keybinds? **NO**, I don't change my keybinds. Because I cba to follow tutorials which have a different keybind than me, so I just use the defaults.

- What DWM version is this? DWM 6.2 :D

## Patches Used

- [Anybar](https://dwm.suckless.org/patches/anybar/) - Cuz I use Polybar, and not the normal DWM bar
- [DWM-IPC](https://dwm.suckless.org/patches/ipc/) - Comes with the build, as Polybar needs IPC for DWM
- [Vanity Gaps](https://dwm.suckless.org/patches/vanitygaps/) - Cuz gaps increase your swag
- [Autostart](https://dwm.suckless.org/patches/autostart/) - To run scripts after startup (e.g compositor, wallpaper manager, statusbar, etc.)
- [Tatami](https://dwm.suckless.org/patches/tatami/) - Cuz I don't like the normal layout

## Screenshot

Here's how it looks like for me

![Screenshot](https://cdn.discordapp.com/attachments/862906833273094167/961970119741939712/unknown.png)

**P.S:** Mine might look different because I am also using Picom, Dmenu, Polybar, Spicetify, and Alacritty alongside DWM

## Installing

If the [DWM IPC](https://github.com/mihirlad55/dwm-ipc) build has any requirements, install those first. Then follow my install steps
```bash
git clone https://github.com/ahnaf-zamil/dwm-ipc
cd dwm
sudo make clean install
```

