# winbox-installer
A simple helper script to install Mikrotik's Winbox in GNU/Linux

## How to install:
Copy and paste this commands to your terminal:

1. `cd /tmp`
2. `git clone https://github.com/mriza/winbox-installer.git`
3. `cd winbox-installer`
4. `sudo ./winbox-setup install` **OR** `sudo bash winbox-setup install`

## Icon cache in GTK based desktop:
Optional step for GTK based desktop, if the icon is not loaded or loaded with wrong size. Update icon cache with this command:

`gtk-update-icon-cache -f -t /usr/share/icons/hicolor`

## How to remove:
If you want to remove winbox, just run this command:

`sudo ./winbox-setup remove` **OR** `sudo ./winbox-setup remove`
