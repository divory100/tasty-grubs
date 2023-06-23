# Tasty Grubs
A collection of GRUB2 themes.

## Installation
1. Clone this repository
2. Open `/etc/default/grub` and set the `GRUB_THEME=` line to `GRUB_THEME=/path/to/theme/directory/you/want/theme.txt`. For example: `GRUB_THEME=/boot/grub/themes/box/theme.txt`. The path must lead to the `theme.txt` file, not the directory.
3. I would recommend moving the themes you want from this repository into `/boot/grub/themes` although this is not necessary.
4. Run `update-grub` and you're good to go! 

*Note: you will likely need to tweak the values (for example `left` and `top`) in the `theme.txt` of the themes as these were built for 640x480 resolution. See 'Troubleshooting' below for more information*

## Themes

### Box
A simple theme with image background. 
Two wallpapers are included by default: `fields.jpeg` and `metropolis.jpeg`. 
These can be easily changed to any suitable image.

![image](https://user-images.githubusercontent.com/76520109/127147286-4790288f-ebc9-4894-85fc-11fa82679fc0.png)

### Box - Large version
Larger variant of the box theme, useful if your menu entries are long

![image](https://user-images.githubusercontent.com/76520109/127011777-57812306-8930-4a12-a475-a4d251e1e1bd.png)



### 'Among Us'
Theme inspired by 2018 mobile game 'Among Us'.

![image](https://user-images.githubusercontent.com/76520109/126898485-a5e5ab06-0790-4ea3-94f7-9a79abd50a15.png)

### 'Among Us' - Large version
Larger variant of the 'Among Us' theme; useful if your menu entries are long and would overflow.

![image](https://user-images.githubusercontent.com/76520109/126898845-523c5ac2-7980-49b9-8a35-74880bcea4c1.png)



### Tesla
Menu entries superimposed on the dashboard screen of a Tesla Model 3. Uses Tesla font.

![image](https://user-images.githubusercontent.com/76520109/126995523-1f722813-02e0-459a-b2dd-9b0b8a1a3055.png)

### Tesla - Sans Serif font
Tesla theme with a Sans Serif font as the Tesla font can sometimes be hard to read.

![image](https://user-images.githubusercontent.com/76520109/126995684-bb3f82a3-7f91-4c09-b6a6-b3a85c969441.png)


## Troubleshooting
You may need to tweak the theme file if your screen resolution means the text is in the wrong place. This is as simple as editing the `left` and `top` attributes in the `+ boot_menu` and `+ label` sections in the corresponding `theme.txt` file for the theme you are using.

## Credits
- Example wallpaper images are from wallhaven.cc
- Tesla font by [Dies](https://www.dafont.com/kayover.d6524) on [dafont.com](https://dafont.com)
