![keyboard map](https://github.com/billyc/en-de-tr-keyboard/raw/master/keyboard-US-International.png 'Full Keyboard Map')

# Billy's Special keyboard layout:<br/>US Layout for coders + German and Turkish too!

This keyboard layout is probably only useful for _Americans with U.S. keyboards who only occasionally need to type in German._ But that's me! And I published it here in case you find it helpful too.

As a software dev, I need all the brackets and punctuation on the US keyboard layout at my fingertips. But I live in Berlin, so I also need to type in German! Typing in German is pretty easy if you switch to the International keyboard, but then all the punctuation ends up in weird places, not to mention always getting Z and Y wrong.

This keyboard layout can do it all. It's based on the US layout, and uses key combinations using the **semicolon key** `;` to trigger the accented letters that I need here in Germany.

<p style="padding: 1rem 1rem; background-color: white">
Why German and Turkish? Well first of all, because I live in Berlin! English, German, and Turkish are the three most common languages spoken in Berlin, probably in that order ;-) so it makes sense to have one keyboard that does all three.<br/>
<br/>
If you just need English and German, that's OK you can safely ignore the Turkish letters below!
</p>

## How to type umlauts and some special characters: ö ü ä ß ç ş ğ ı

Every key on this keyboard works exactly like the regular U.S. keyboard with the exception of the `semicolon (;)` key which triggers a two-key combination:

**For umlauts etc:**

- First type `;` -- nothing will show up on your screen
- Then type the letter: `o` `u` `a` `s` `c` `x` `i`.
- The umlauted or accented character will magically appear! öüäßçşğı

**For Capital Letters:**

- First type `;` -- nothing will show up on your screen
- Then type the CAPITAL letter: `SHIFT` plus `o` `u` `a` `s` etc.
- The capital letter will magically appear: Ö Ü Ä etc.

**To type a real semicolon:**

- Press `;` twice ("semi-semi")
- Or press "semi-space" to get a semicolon followed by a space.

That's it!

| Letter | How to Type It |
| ------ | -------------- |
| `;`    | `;` + `;`      |
| `ö`    | `;` + `O`      |
| `ü`    | `;` + `U`      |
| `ä`    | `;` + `A`      |
| `ß`    | `;` + `S`      |
| `ç`    | `;` + `C`      |
| `ş`    | `;` + `X`      |
| `ğ`    | `;` + `G`      |
| `ı/İ`  | `;` + `I`      |
| `€`    | `;` + `E`      |

Remember, to produce a Capital Letter, press `;` first and **then** `SHIFT` and the letter.

**About that Turkish `İ`**

The Turkish `I` and `İ` are a bit strange since the English "i" is either dotted or not, depending on whether it's lower or upper case. Turkish has two different i letters, one dotted and one undotted -- and each has a lower and upper case version! While on a real Turkish keyboard, these are two separate keys, here we just put them all on the I key and you use the `;` combos for the Turkish versions.

# Installation

## 1. Windows

The provided setup file should work on Windows 7/8/10/11.

- Download [intl-bc.zip](https://github.com/billyc/en-de-tr-keyboard/raw/master/windows/intl-bc-keyboard.zip)
- Unzip the contents, and run `setup.exe`.
- Then go to your system _Region & Language_ control panel. Under the English language options, you should be able to add/remove the "US International Alternate + Turkish" keyboard.
- For my own system, I removed the "US Qwerty" keyboard so that Windows always defaults to this layout. Otherwise you may need to choose it from the language icon near your system clock/tray.

## 2. Mac

This is tested on both Intel and M1 macs.

- Download [billy-en-de-tr-keyboard.dmg](https://github.com/billyc/en-de-tr-keyboard/raw/master/mac/billy-en-de-tr-keyboard.dmg)
- Run the .dmg file installer
- Select it using the Keyboard Control Panel

## 3. Linux

The files mentioned below can be found in <https://github.com/billyc/keyboard/linux>

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
