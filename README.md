# wallpapers
A lot of hand picked wallpapers together with a shell script that sets one of them as your active wallpaper randomly

Installation
---

Clone this repository `git clone https://github.com/Bowuigi/wallpapers ~/Images/wallpapers`

Place `randwall` anywhere in your $PATH, I recommend /usr/local/bin with `sudo mv ~/Images/wallpapers/randwall /usr/local/bin/randwall`

Remove the `.git` directory and the README.md with `rm -rf ~/Images/wallpapers/randwall/.git ~/Images/wallpapers/randwall/README.md`, to upgrade, just repeat the process specified here.

Add this line before the `exec` in your .xinitrc or to your window manager's autostart

`randwall`

Enjoy!
