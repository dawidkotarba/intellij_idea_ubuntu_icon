## Create IntelliJ IDEA icon in Ubuntu:

- Create file:
```
sudo vim /usr/share/applications/intellij.desktop
```

- Add the following:
```
[Desktop Entry]
Version=18.1
Type=Application
Terminal=false
Icon[en_US]=/home/dawidkotarba/_dev/idea/bin/idea.png
Name[en_US]=IntelliJ
Exec=/home/dawidkotarba/_dev/idea/bin/idea.sh
Name=IntelliJ
Icon=/home/dawidkotarba/_dev/idea/bin/idea.png
```

- Mod permissions:
```
sudo chmod 644 /usr/share/applications/intellij.desktop
sudo chown root:root /usr/share/applications/intellij.desktop
```
