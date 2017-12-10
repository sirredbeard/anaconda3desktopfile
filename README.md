# anaconda3desktopfile
A .desktop file for Anaconda3

## Instructions

Clone this repository and enter directory.

```
git clone https://github.com/sirredbeard/anaconda3desktopfile.git
cd anaconda3desktopfile/
```

Edit path to your anaconda3 location in your editor of choice. Default is ~/anaconda3.

```
nano anaconda.desktop (~/anaconda3, /opt/anaconda3, etc.)
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
