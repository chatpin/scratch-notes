Wed 23 Sep 2020 08:03:00 BST

# vim/buffers


#### when using the 'gf' command it's useful to keep in mind that when the new buffer appears, the previous one(s) remain open in the background.

| command    | desciption                  |
| ---------- | --------------------------- |
| :b [Num]   | move to that buffer (window) |
| :ls        | shows buffers                |
| :[N] bd!   | unload buffer, changes lost  |
| :[N] bd    | if buffe was changed, this fails |
| :% delete  | delete all buffers           |
| :[N] sb    | split window and edit buffer |
| :Ctrl-w    | followed by h, j, k, or l - switch pane |

___
[vim index](./vi-index.md)
[vim help](./vi-help.md)
[home](./vim-index.md)
