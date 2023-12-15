### This is a forked and edited to my liking.. removing the win11 png and adding blur
#### This will be the SDDM that I will be adding into my Hyprland Scripts 


<h2 align="center">🗼 Tokyo House SDDM Theme 🗼</h2>

<p align=center>
A Tokyo Night theme variant for the <a href="https://github.com/sddm/sddm">SDDM Login Manager</a>
</p>

<h2 align=center>Preview</h2>
<center>
<img src="./Previews/1.png" alt="preview-1">
<details>
<summary align=center>More Previews</summary>
<img src="./Previews/2.png" alt="preview-2">
<img src="./Previews/3.png" alt="preview-4">
<img src="./Previews/4.png" alt="preview-3">
</details>
</center>

Updated screenshots to follow

## Install
### From sources
> _Assumes that you've installed and configured SDDM correctly_ (if not [read more](https://wiki.archlinux.org/title/SDDM))

>  Please make sure you have the following dependencies installed:
>  `qt5-quickcontrols2`, `qt5-graphicaleffects`, `qt5-svg` 

1. Open terminal, and clone the repository with:

   ```sh
   git clone https://github.com/JaKooLit/tokyo-house.git ~/tokyo-night-sddm
   ```

2. Them move it as follows:

   ```sh
   sudo mv ~/tokyo-house /usr/share/sddm/themes/
   ```

## Configure

Edit the `/etc/sddm.conf.d/10-theme.conf` (with any text editor with **raised** privileges), so that it looks like this:

```sh
sudo nano /etc/sddm.conf.d/10-theme.conf  # use any text editor with raised privileges
---

[Theme]
Current=tokyo-house
   ```

### Language and time format
- This is
- You can also change the time format.
- To change the default wallpaper put desired image in the `tokyo-house/Backgrounds/` folder and add the name of the image followed by its extension (`.jpg` or `.png`) in `theme.conf` file.
- You can also customize it further if you wish in the `theme.conf`
(blur, form position, etc).




## Credits
- Full credit goes to original autor [`LINK`](https://github.com/rototrash/tokyo-night-sddm)

- Based on the theme [`Sugar Dark for SDDM`](https://github.com/MarianArlt/sddm-sugar-dark) by [**MarianArlt**](https://github.com/MarianArlt).
- AUR Package by [**julian-poidevin**](https://github.com/julian-poidevin)

## License

[GNU Lesser General Public License v3.0](LICENSE)
