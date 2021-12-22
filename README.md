**WARNING:If you are on Ubuntu or an Ubuntu-based distribution you'll need to do `sudo apt install libx11-dev` before using Pine-jinx!**

# Pine-jinx
<img align="left" alt="Frogjinx" width="22px" src="https://cdn.discordapp.com/attachments/780529926520438854/802958006282092624/FrogRyujinx.svg" />A local Ryujinx installer for linux

This installer does not create an alias since the way to do this is different for every shell (eg. sh, bash, zsh, fish, ksh)

The purpose of the installer is to place Ryujinx inside ~/.local/share/Ryujinx, setup a desktop entry with optional optimizations (per GPU vendor and/or gamemode) as well as setup mimetypes for Switch binaries (eg. NSP, XCI).

Usage:
Open a terminal, paste <br>
`bash -c "$(curl -s https://raw.githubusercontent.com/edisionnano/Pine-jinx/testing/pinejinx.sh)"` <br>
and hit enter

## Note
This installs the latest master build, to get LDN use</br>
`bash -c "$(curl -s https://raw.githubusercontent.com/edisionnano/Pine-jinx/LDN/pinejinx.sh)"`
</br>LDN is installed at a different location so that you can have both together at the same time.
<br>For the re-nice feature to work you need to run these two terminal commands:
<br>`sudo groupadd gamemode`
<br>`sudo usermod -a -G gamemode $USER`
