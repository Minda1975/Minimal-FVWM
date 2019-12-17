# Minimal-FVWM
Minimal Fvwm configuration for Debian Buster system. With only 866 pkg you can hace a fully working system without bloating stuff. 

FVWM config is shamely stolen from [Knuth](https://www-cs-faculty.stanford.edu/~knuth/programs/.fvwm2rc) Fvwm config and adapted for modern FVWM config. Maybe it is the best FVWM config. It have 4 virtual desktops, buttons to switch virtual desktops, asclock, for clock and xload (as system load viewer). This is nicely integated with FVWMButtons module. 

Dependencies:

You can install whatever you want, but i use these cute apps:

`Transmission-gtk`-for torrents, clock-`asclock`, `mpv`-for video, `mpg123` and `moc`-for audio. For web browsing i use `Firefox-esr` and `w3m`, for viewing pictures i use `sxiv`, for irc chat-`irssi`. For working with files i use simple file managers: `fff` (it is in directory `~/.bin`) `nnn` and `xfe`. Also i use cutty terminal apps:`screenfetch-dev`, `neofetch`, `pfetch`and `pfe`.

For monitoring system resources, i use `xload`, `top` and `htop`. 

My main terminals is good and fast `xterm` and `rxvt-unicode`. Config for colors and fonts is in `.Xresource` file.

My version control system os `git`.

In my system i do not use pulseaudio. Only `alsa` with `alsamixer`.

P.S.

Do not forget add directory `~/.local/bin` to your path! This is not necessary, but much comfortable to work!

P.S.S.

Also, i added color schemes for window decorations (it is in CdeColors folder). This folder contains 41 color themes with names such Alpine, Arizona etc. Just copy color definition to fvwm config (replace existed colors) and restart window manager.

![Screenshot](screen.png?raw=true "Clear")
![Screenshot](screen_1.png?raw=true "Notification")
![Screenshot](screen_2.png?raw=true "Bussy")
![Screenshot](screen_3.png?raw=true "Bussy")
![Screenshot](screen_4.png?raw=true "Bussy")



