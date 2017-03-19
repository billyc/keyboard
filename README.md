# US International Alternate + Turkish Keyboard

This is a Windows keyboard layout based on the excellent 
"US International Alternate" layout, available on Ubuntu.
It uses "AltGr" -- combinations of the `right-ALT` key + letters to
produce non-English letters from most Western European languages.

![keyboard map](https://github.com/billyc/keyboard-intl-tr/raw/master/keyboard-US-International.png "Full Keyboard Map")

I've added the three missing Turkish letters (ğ ş and ı).

You can use this one layout to type Turkish, German, Spanish, French, Italian... without 
messing up any keys already on your keyboard. Awesome!

The Turkish `I` and `İ` are a bit strange since the English "i" is either dotted or not depending on whether it's lower or upper case. I've added two separate key mappings for the two Turkish versions of i, as that is how Turks think about them: they are different letters. What this means in practice is that you will only need the lowercase ı and the uppercase İ. They're on different keys. I thought about putting those on one key, but to a Turk that would be really weird. Let me know how this works for you.

### Key combinations for Turkish letters

On a US keyboard, `AltGr` is the **right ALT key** -- the ALT key to the right of the spacebar. 

* To produce the letter below, hold down the `RIGHT-ALT` key and press the letter.
* To produce a Capital Letter, hold down **both** `SHIFT` and `RIGHT-ALT` and then press the letter.

|Letter|How to Type It|
|------|--------------|
|  `ç`  | `RIGHT-ALT` + `,` |
|  `ş`  | `RIGHT-ALT` + `x` |
|  `ğ`  | `RIGHT-ALT` + `g` |
|  `ı`  | `RIGHT-ALT` + `h` |
|  `İ`  | `RIGHT-ALT` + `j` -- but also hold `SHIFT` for `İ`|
|  `ö`  | `RIGHT-ALT` + `p` |
|  `ü`  | `RIGHT-ALT` + `y` |

**Circumflex**

Some older Turkish words still use the circumflex `^` e.g. *bekârım*. You can type those by using what's called "dead key" combinations:

* First type `RIGHT-ALT`+`SHIFT`+'6' (the circumflex key) -- nothing will show up on your screen
* Then type the vowel you want to get the little hat: â, ô, ê will magically appear.

### Installation

The provided setup file should work on Windows 7 and up.

- Download [intl+tr.zip](https://github.com/billyc/keyboard-intl-tr/raw/master/intl%2Btr.zip)
- Unzip the contents, and run `setup.exe`. 
- Then go to your system *Region & Language* control panel, Under the English language options, you should be able to add/remove the "US International Alternate + Turkish" keyboard. 
- For my own system, I removed the "US Qwerty" keyboard so that Windows always defaults to this one. Otherwise you may need to pick the keyboard from the `ENG` icon near your system clock / tray.

### Full Layout

You can see all the US International Alternate mappings here: 

![keyboard map](https://github.com/billyc/keyboard-intl-tr/raw/master/keyboard-US-International.png "Full Keyboard Map")

Props to http://keyboards.jargon-file.org for the initial KLC file!

