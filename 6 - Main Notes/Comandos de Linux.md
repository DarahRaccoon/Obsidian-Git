Status: #persistent

tags: [[linux]], 

---
# .deb packages
## Install[^1]
```
sudo dpkg -i DEB_PACKAGE
```
## Remome[^1]
```
sudo dpkg -r PACKAGE_NAME
```
# .AppImage
## Install (Make it executable)
```
chmod a+x exampleName.AppImage
```
## Execute
``` 
./exampleName.AppImage
```
## Register as a desktop file
```
Move it to an appropriate path, like:

	~/.local/bin.

Extract the AppImage, run:

	{app}.AppImage --appimage-extract

a directory will be created called squashfs-root in the current working directory.

Enter the directory squashfs-root and copy the desktop launcher {app}.desktop to

	~/.local/share/applications

Edit the desktop launcher to point to the path of the AppImage followed by

	%F
	%U
	%u
i.e.
	Exec=/home/username/.local/bin/inkscape.AppImage %F

Give the .desktop file executable permissions:

	chmod +x ~/.local/share/applications/org.inkscape.Inkscape.desktop

Remove the directory squashfs-root
```
# Cache[^2]
```
sudo apt update`
sudo apt upgrade`
sudo apt autoremove --purge`
sudo apt clean`
sudo journalctl --vacuum-time=7d`
sudo rm -rf /var/tmp/*`
```
# Texlive
## Install
## Uninstall
	sudo apt-get purge texlive*
	sudo rm -rf /usr/local/texlive/*
	sudo rm -rf ~/.texlive*
	sudo rm -rf /usr/local/share/texmf
	sudo rm -rf /var/lib/texmf
	sudo rm -rf /etc/texmf
	sudo apt-get remove tex-common --purge
	rm -rf ~/.texlive
	find -L /usr/local/bin/ -lname /usr/local/texlive/*/bin/* | xargs -r rm


[^1]: [[Installing .deb packages]]
[^2]: Deepseek
