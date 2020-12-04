# Linux English/German/Turkish keyboard instructions

These keyboard files will give you one keyboard that lets you type
in all three languages at once. You'll need root/sudo privileges 
to enable this keyboard layout.

## USAGE: Semicolon key!

Once installed and selected as your input keyboard (see below), only
one thing about your keyboard changes: the SEMICOLON key now behaves
differently. Pressing `;` now waits for you to type a second key before it 
puts the text on the screen:
    
    SEMICOLONS:   
    semi + semi:  semicolon
    semi + space: semicolon followed by space

    GERMAN LETTERS:
    semi + a,o,u: ä,ö,ü  (And shift key as usual for capitals)
    semi + s:     ß

    TURKISH LETTERS:
    semi + c:     ç/Ç
    semi + x:     ş/Ş
    semi + g:     ğ/Ğ
    semi + i:     ı/İ

That's it! You can also access all of those letters with `Alt(Right)` + letter,
if that's your preference.


## INSTALL INSTRUCTIONS

1) Copy the two files using sudo to their proper places:

```bash
sudo cp usr-share-x11-xkb-symbols-us /usr/share/X11/xkb/symbols/us 
sudo cp usr-share-x11-xkb-rules-evdev.xml /usr/share/X11/xkb/rules/evdev.xml 
```

2) Copy the XCompose file to your home folder at ~/.XCompose

3) From Gnome Settings, choose Regional & Language, and under Input Sources:
   - Press `+`
   - Choose "English (United States)"
   - Select "English (Billy-En/De/Tr)" 
   - Click `Add` and close.

You may need to logout/login to select your new keyboard from the top-right system bar.


