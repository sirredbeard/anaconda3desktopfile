# anaconda3desktopfile
A .desktop file for [Anaconda3](https://www.anaconda.com/download/#macos) for XFCE4 and other -nix desktop environments.

![anaconda](anaconda.png)

## Instructions

Clone this repository and enter directory.
```
git clone https://github.com/sirredbeard/anaconda3desktopfile.git
cd anaconda3desktopfile/
```

Edit path to your anaconda3 location (e.g. /home/sirredbeard/anaconda3, /opt/anaconda3, etc.) in your editor of choice.
```
nano anaconda.desktop 
```

Copy everything into place.
```
cp anaconda.* ~/.local/share/applications/
```

Clean up.
```
cd ..
rm -r anaconda3desktopfile/
```
