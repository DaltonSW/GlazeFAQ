<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

# GlazeFAQ

FAQs (and tips) for GlazeWM, a "tiling window manager for Windows inspired by i3 and Polybar".  
Check it out [here](https://github.com/glzr-io/glazewm).

## How do I...

### Uninstall Glaze?
- Just delete the exe. If you wish to remove config settings too, go to your home folder and delete the hidden `.glazewm` folder

### Make Glaze run on startup?
Find the exe on your computer. Right Click and make a Shortcut, then cut the created Shortcut. Now hit `Win+R` to open the `Run` prompt. Enter `shell:startup` to get to the Windows startup folder. Paste your shortcut here. That's it!

## Why is/are my...

### Icons not showing up?
You need to be using a Nerd Font. Download one from [here](https://www.nerdfonts.com/)

### Icon spacing funky?
- Try the different font types that might've come with your download. The Propo or Mono variations might solve this issue. 
- You can also change the font size of just the icon to see if that helps the spacing
- Try adding/removing a space character between the icon and the component value
- Try adjusting the padding of the component, if your icon borders the left or right edge of the component
