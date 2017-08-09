![keyboard map](https://github.com/billyc/keyboard-intl-tr/raw/master/keyboard-US-International.png "Full Keyboard Map")

# US International Alternate + Turkish Keyboard

Typing in Western European languages on Windows is pretty easy if you turn on the International keyboard, but getting the extra Turkish letters is a little bit trickier.

This is a Windows keyboard layout that can do both.
It uses combinations of the `right-ALT` key + letters to
produce the accented letters and symbols needed for most Western European languages. The "US International Alternate" keyboard (found on Linux) already has ö, ü, and ç; all I did was add the three missing Turkish letters: ğ, ş, and ı.

It is probably most useful for Americans with U.S. keyboards who only occasionally need to type in other languages. You can use this layout to type Turkish, German, Spanish, French, Italian... without changing any of the existing keys on your keyboard. Especially for coders, it's maddening to lose your punctuation keys! Now you don't have to.

### Key combinations for Turkish letters

On a US keyboard, the `AltGr` key is the **right ALT key** -- the ALT key to the right of the spacebar. 

* To produce the letter below, hold down the `RIGHT-ALT` key and press the letter.
* To produce a Capital Letter, hold down **both** `SHIFT` and `RIGHT-ALT` and then press the letter.

|Letter|How to Type It|
|------|--------------|
|  `ç`  | `RIGHT-ALT` + `,` |
|  `ş`  | `RIGHT-ALT` + `x` |
|  `ğ`  | `RIGHT-ALT` + `g` |
|  `ı`  | `RIGHT-ALT` + `h` |
|  `i`  | `RIGHT-ALT` + `j` -- and hold `SHIFT` for `İ`|
|  `ö`  | `RIGHT-ALT` + `p` |
|  `ü`  | `RIGHT-ALT` + `y` |

**The Turkish `İ`**

The Turkish `I` and `İ` are a bit strange since the English "i" is either dotted or not depending on whether it's lower or upper case. I've added separate key mappings for the two Turkish versions of i, since that is how Turks think about them: they are different letters. In practice, you will only need the lowercase ı and the uppercase İ. They're on different keys. I thought about putting them on one key, but to a Turk that would be weird. Let me know how this works for you.

**Circumflex**

Some older Turkish words still use the circumflex `^` e.g. *bekârım*. You can type those by using what's called "dead key" combinations:

* First type `SHIFT`+`RIGHT-ALT`+`6` (the circumflex key) -- nothing will show up on your screen
* Then type the vowel. The letter with the cute little hat will magically appear: â, ô, ê, î

### Installation

The provided setup file should work on Windows 7 and up.

- Download [intl+tr.zip](https://github.com/billyc/keyboard-intl-tr/raw/master/intl%2Btr.zip)
- Unzip the contents, and run `setup.exe`. 
- Then go to your system *Region & Language* control panel. Under the English language options, you should be able to add/remove the "US International Alternate + Turkish" keyboard. 
- For my own system, I removed the "US Qwerty" keyboard so that Windows always defaults to this layout. Otherwise you may need to choose it from the language icon near your system clock/tray.

### Full Layout

You can see all the US International Alternate mappings here: 

![keyboard map](https://github.com/billyc/keyboard-intl-tr/raw/master/keyboard-US-International.png "Full Keyboard Map")

---

# OOPS! Update:

Well, I decided I didn't like the fact that the umlauted a, u, o keys were all bumped out of the way in the International Layout for áccentéd letters cónvenient for Spanish or French. I don't speak Spanish or French! So, I've moved the umlauted letters to the keys where they belong: ALT-A, ALT-O, and ALT-U now produce Ä, Ö, and Ü. Tough titties, Spanish speakers. The Billy-fied version is here:
- - Download [intl+bc.zip](https://github.com/billyc/keyboard-intl-tr/raw/master/intl%2Bbc.zip)


---
Built with the [Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx). Props to [keyboards.jargon-file.org](http://keyboards.jargon-file.org) for the initial KLC file!

