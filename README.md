# wallpapers
A lot of hand picked wallpapers together with a shell script that sets one of them as your active wallpaper randomly

Installation
---

Clone this repository `git clone https://github.com/Bowuigi/wallpapers ~/wallpapers`

Copy (do not move) `randwall` to anywhere in your $PATH, I recommend /usr/local/bin with `sudo cp ~/wallpapers/randwall /usr/local/bin/randwall`

To get the latest wallpapers, run `git pull` from ~/Images/wallpapers

Add this line before the `exec` in your .xinitrc or to your window manager's autostart

`randwall`

Enjoy!
