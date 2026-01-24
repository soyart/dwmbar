# dwmbar

dwmbar is a Go status bar program with configuration support.

It aims to be more power efficient than the [original shell script](https://gitlab.com/artnoi/unix/-/blob/544bb48ac5b6278cda88f6e5af87e086a867cfdf/dotfiles/linux/.config/dwm/dwmbar.sh).

Compared to the shell version, the new dwmbar produces way less page faults,
and forks much less children when poll intervals match.

However, it consumers more *idle* memory than the shell version.
