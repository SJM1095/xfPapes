# xfPapes
A simple bash script to change multiple wallpapers on XFCE and apply pywal theme styling in one simple command.

# Before Using

**Important:** This bash script executes pywal on use to change your system theme. If you do not have pywal installed, please remove any line containing ```wal -i "/path/to/wallpaper/folder/$1" && ```.

Before using xfPapes, please modify the script to meet your needs. I currently have 4 monitors, as such I have included conditional arguments to select how many monitors I wish to apply the wallpaper to. If you have less or more than 4 monitors, please modify the script and add/remove the relevant lines of code.

Additionally, please modify any lines containing ```"/path/to/wallpaper/folder/$1"``` and insert the path to the folder where you keep your wallpapers. Once these changes are made, you should be good to go!

# Usage
To use xfPapes simply execute the script and pass an argument to it.

Example: ```./xfPapes wallpaper.png```
