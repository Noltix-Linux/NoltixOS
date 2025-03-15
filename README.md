![2025-01-01_17-34-removebg-preview](https://github.com/user-attachments/assets/a63f89f5-0b10-4983-80ee-a8f69e4c5128) 

#                               NoltixOS: An <a href="https://awesomewm.org/">awesome</a> distribution!

NoltixOS is an GNU/Linux distro that is based off Arch and it's goal is to make Arch Linux accesible to more people.

It uses ALCI's config for the Calamares Installer and comes with dwm in the live session, and AwesomeWM & SDDM after the installation.

Notice: If you try to manually build the iso with mkarchiso, you may come across the fact it doesnt have the calamares installer, well to fix that just add ALCI's config for calamares (https://github.com/arch-linux-calamares-installer/alci-calamares-config) In /airootfs/etc and then you're pretty much done.


# Feautures
* Fish shell preinstalled

    Fish is an modern, great and advanced shell for Linux, macOS etc.


* Default WM is AwesomeWM

    Awesome window manager is an advanced Window manager based off dwm. It is written in C and Lua. You can also install themes for the WM to personalize it.


* Graphical Installer
   
     You may already know this but NoltixOS uses the Calamares Installer to quickly get the OS setup.

* SDDM built-in

   SDDM is an great display manager for Linux. It is the one that NoltixOS normally comes with.

# Installation
1. Grab yourself the ISO image from https://www.naturl.link/awer (Link may change over time, Due to newer versions etc.)
2. Flash it to an USB Stick.

    If you are using Windows, I reccomend using Rufus.
3. Boot from the USB (You can find tutorials based on your manufacturer.)
4. Enter the one that is appropriate to your PC/Laptop/anything.
5. Wait, Install using the ALCI Config for Calamares

To install a Friendlier GUI after setup,

install using sudo pacman:
vicious (otherwise The theme won't work)
alacritty (otherwise Terminal won't work and you won't be able to run any other program)
wireless_tools (otherwise Network widget won't work)
redshift (otherwise Brightness widget won't let you setup color temperature)
geoclue (otherwise Brightness widget won't compute dusk time and dawn time for your geolocation)
PulseAudio or PipeWire (otherwise Volume widget won't let you choose input/output devices)

then:
> git clone https://github.com/Relz/awesome-wm-theme.git ~/.config/awesome



This software is licensed under the **<a href="https://www.gnu.org/licenses/gpl-3.0.html">GNU General Public License 3.0</a>**.


