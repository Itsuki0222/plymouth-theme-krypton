# plymouth-theme-krypton

plymouth-theme-kryptonはmonoarchをforkして作られたKrypton Linux用のPlymouthテーマです。

# Installation
Files should be placed in the Plymouth themes directory,
which is usually `/usr/share/plymouth/themes`. You may install the theme by simply cloning the repository:

    # cd /usr/share/plymouth/themes/ 
    # git clone https://github.com/farsil/monoarch.git 

Remember to change the Plymouth theme:

    # plymouth-set-default-theme -R monoarch

# Removal
Simply remove the directory:

    # rm -rf /usr/share/plymouth/themes/monoarch
    
Remember to change your theme again otherwise Plymouth will fall back to its 
default one.

# Credits
DeviantArt user Kahlil88, author of the
[paw-arch](http://kahlil88.deviantart.com/art/Paw-Arch-Plymouth-Theme-208418769)
theme I used it as a base to build my code.
 
Arch Linux logo taken from
[https://www.archlinux.org/art/](https://www.archlinux.org/art/).

Spinner pictures and a large part of code taken from the default Plymouth themes.
