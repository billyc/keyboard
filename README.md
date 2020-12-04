![keyboard map](https://github.com/billyc/en-de-tr-keyboard/raw/master/keyboard-US-International.png "Full Keyboard Map")

# US Keyboard Layout + German + Turkish: 3-in-1!

Typing in German on Windows and Linux is pretty easy if you turn on the International keyboard, but getting those extra Turkish letters is a bit trickier.

This is a keyboard layout for Windows and Linux that can do all three. It's based on the US layout, and uses combinations of the `right-ALT` key + letters to
produce the accented letters and symbols needed for German and Turkish.

This keyboard is probably only useful for Americans with U.S. keyboards who only occasionally need to type in those other languages. That's me!

    Why German and Turkish? Well first of all, because I live in Berlin!
    And second of all, English, German, and Turkish are the three most
    common languages spoken in Berlin, probably in that order ;-) so
    it makes sense to have one keyboard that does all three.

## Key combinations for German and Turkish letters

On a US keyboard, the `AltGr` key is the **right ALT key** -- the ALT key to the right of the spacebar.

- To produce the letter below, hold down the `RIGHT-ALT` key and press the letter.
- To produce a Capital Letter, hold down **both** `SHIFT` and `RIGHT-ALT` and then press the letter.

| Letter | How to Type It    |
| ------ | ----------------- |
| `ö`    | `RIGHT-ALT` + `O` |
| `ü`    | `RIGHT-ALT` + `U` |
| `ä`    | `RIGHT-ALT` + `A` |
| `ß`    | `RIGHT-ALT` + `S` |
| `ç`    | `RIGHT-ALT` + `C` |
| `ş`    | `RIGHT-ALT` + `X` |
| `ğ`    | `RIGHT-ALT` + `G` |
| `ı/İ`  | `RIGHT-ALT` + `I` |

**About that Turkish `İ`**

The Turkish `I` and `İ` are a bit strange since the English "i" is either dotted or not, depending on whether it's lower or upper case. Turkish has two different i letters, one dotted and one undotted -- and each has a lower and upper case version! While on a real Turkish keyboard there would be two separate keys, here we just put them all on the I key and you have to use the alt key for the (to me) weird Turkish versions. Let me know how this works for you.

**Circumflex**

_EDIT -- this no longer works, ignore this_

Some older Turkish words still use the circumflex `^` e.g. _bekârım_. You can type those by using what's called "dead key" combinations:

- First type `SHIFT`+`RIGHT-ALT`+`6` (the circumflex key) -- nothing will show up on your screen
- Then type the vowel. The letter with the cute little hat will magically appear: â, ô, ê, î

# Installation

## 1. Windows

The provided setup file should work on Windows 7 and up.

- Download [intl+bc.zip](https://github.com/billyc/en-de-tr-keyboard/raw/master/windows/intl%2Bbc.zip)
- Unzip the contents, and run `setup.exe`.
- Then go to your system _Region & Language_ control panel. Under the English language options, you should be able to add/remove the "US International Alternate + Turkish" keyboard.
- For my own system, I removed the "US Qwerty" keyboard so that Windows always defaults to this layout. Otherwise you may need to choose it from the language icon near your system clock/tray.

## 2. Linux

The linux keyboard also has the `semicolon` key as a "special key" which you must
press and then follow by a second key to get the letter you want. Semi-semi produces
a real semicolon; semi-space produces a semi followed by a space (very logical!) and
semi followed by one of a-o-u-s-x-g-i gets you the fancy letters.

The files mentioned below can be found in <https://github.com/billyc/turkish-keyboard/linux>

1. Copy the following two files using sudo to their proper places:

   ```bash
   sudo cp usr-share-x11-xkb-symbols-us /usr/share/X11/xkb/symbols/us
   sudo cp usr-share-x11-xkb-rules-evdev.xml /usr/share/X11/xkb/rules/evdev.xml
   ```

2. Copy the XCompose file into your home folder as `~/.XCompose`

3. From Gnome Settings, choose Regional & Language, and under Input Sources:
   - Press `+`
   - Choose "English (United States)"
   - Select "English (Billy-En/De/Tr)"
   - Click `Add` and close.

You may need to logout/login to select your new keyboard from the top-right system bar.

### Make Your Own Layout

Feel free to fork and make your own keyboards!

Windows: Built with the [Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx). Props to [keyboards.jargon-file.org](http://keyboards.jargon-file.org) for the initial KLC file!

Linux: I followed this blog to figure out how to do it: <http://karols.github.io/blog/2013/11/18/creating-custom-keyboard-layouts-for-linux/>
