Introduction
==============
use you gmail as your note place.
When you use this plugin, your can send the current text to your gmail, within the default inbox named "gnote",  
the subject of your note will be your filename without suffix by default, so same filename(without suffix) will be in same dialogue. Just have a try, you'll see the effect.

Why I write this plugin
=======================
I'd like to write note in my vim. I cannot imagination there is no vim when I am noting.  
So I write this.
  
Requirements
===============
* vim python2 support: vim-gnote is based on python2, so your vim should be builded with python2 support.  
* gmail account
  
Configuration
===============
* account settings
```
let g:gnote_gmail_username="your gmail username"
let g:gnote_gmail_password="your gmail password"
```
  
* change the default mailbox name
```
let g:gnote_gmail_mailbox="NOTES"
```
  
* keybord (you can also set the short cuts in your vim config), for example:
```
map <leader>gn <esc>: call Gnote() <cr>
```

TODO
=======
* attchment supported

vim:tw=78:ts=8:ft=help:norl:noet:fen:fdl=0

