# misc-gnome-tray-icons
Miscellaneous Gnome-style Tray Icons

![Screenshot from 2022-11-26 23-05-17](https://user-images.githubusercontent.com/3295286/204120867-6594a2d7-2e6f-481e-9fc2-736eb79f7cd7.png)

## What is this?

Several B&W/monochrome replacement tray icons I use with the Gnome Extension for [AppIndicator and KStatusNotifierItem Support](https://extensions.gnome.org/extension/615/appindicator-support/).

I'm just sharing them here in case someone finds them useful.

## How to replace tray icons?

1. To find the name of an existing tray icon press ALT+F2, type `lg` -> Enter. This will open the Gnome Looking Glass Inspector
2. Click the top left target icon, then click the tray icon you want to identify the name of
3. Note the number in `r(0)`. Type e.g. `r(0)._indicator._proxy.Id` -> Enter
4. The icon name should now be returned
5. You can now use that exact name with the path to the icon, to replace the icon, like so:

![Screenshot from 2022-11-26 23-36-07](https://user-images.githubusercontent.com/3295286/204120945-c5c33b51-d977-4442-afae-35c528c640ab.png)

6. Only some apps require Attention icons
7. To exit Looking Glass activate the panel and press ESC

_Note: There are also a bunch of useful icons in /usr/share/icons/ you can use. I've just made some that I couldn't find in the Gnome-style_

## Other notes

- I find the icons look best at size 18, so that's what i recommend configuring the extension to use

![image](https://user-images.githubusercontent.com/3295286/204121322-34589ac0-10d4-4ce2-b0df-636a4192b941.png)
