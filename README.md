# dwmbar

dwmbar is a Go status bar program with configuration support.

It aims to be more power efficient than the original shell script.

Compared to the shell version, the new dwmbar produces way less page faults,
and forks much less children when poll intervals match.

However, it consumers more *idle* memory than the shell version.
