# Tasty Grubs 🪲
A collection of GRUB2 themes.

## Installation (Themes)
Clone this repository, then open up `/etc/default/grub` and set the `GRUB_THEME=` line to `GRUB_THEME=/path/to/theme/directory/you/want/theme.txt` for example `GRUB_THEME=/boot/grub/themes/amogus/theme.txt` The path must be to the `theme.txt` not the directory.
I would recommend moving the themes you want from this repository into `/boot/grub/themes`

After this make sure to run `update-grub` and you're good to go! 

*Note: you may need to tweak the values (for example `left` and `top` in the `theme.txt` of the themes as these were built for 640x480 resolution.*

## Installation (GRUB init tunes)
To use one of the GRUB init tunes (see `themes/tunes.md` for a list) simply edit the `GRUB_INIT_TUNE=` line of `/etc/default/grub` to whatever tune you desire, for example `GRUB_INIT_TUNE="500 262 2 311 2 349 2 370 2 349 2 311 2 262 5 233 1 294 1 262 2"`

## Themes

**Amogus**

The classic Amogus grub2 boot theme.

*Also comes with accompanying GRUB init tune!*

![image](https://user-images.githubusercontent.com/76520109/126898485-a5e5ab06-0790-4ea3-94f7-9a79abd50a15.png)

**Amogus Large**

The large variant of the Amogus theme, useful if your menu entries are long and would overflow.

![image](https://user-images.githubusercontent.com/76520109/126898845-523c5ac2-7980-49b9-8a35-74880bcea4c1.png)


## Troubleshooting
You may need to tweak the theme file if your screen resolution means the text is in the wrong place. This is as simple as editing the `left` and `top` attributes in the `+ boot_menu` and `+ label` sections in the corresponding `theme.txt` file for the theme you are using.
