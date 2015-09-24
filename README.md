# Lightweight sidebar patch for mutt

The sidebar patch adds a folder list with counters on the left of mutt.

The original patch, which can be found [here](http://www.lunar-linux.org/mutt-sidebar/), does not handle correctly huge folders (> 5,000 emails) and freezes. The lightweight sidebar patch disables the counter stuff for the Maildir folder `cur/`.

Check tags for specific versions.

More information: https://kdecherf.com/blog/2013/07/25/mutt-a-lightweight-sidebar-patch-for-heavy-folders/
