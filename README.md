# TypeBeastXD+ Home Edition

<img src="https://raw.githubusercontent.com/ChrisChrisLoLo/TypeBeastXDPlus/main/keyboard-layout.png">
A minimal 4x10 keyboard layout focused on text editing and programming

## What is TypeBeastXD+ Home Edition?
TypeBeastXD+ Home Edition (or TypeBeastXD+ for short) is a 4x10/38 key layout that pulls inspiration from the OLKB Planck layout as well as the [Miryoku layout](https://github.com/manna-harbour/miryoku). It's generally well suited for casual keyboard use as well as programming, and is catered towards ortholinear boards. It focuses more on general "productivity" and an easier learning curve moreso than ergonomics. I consider it to be a smaller Planck layout that pulls some tricks from Miryoku rather than a Miryoku layout with more keys.

Since keyboard layouts at this size require some degree of customization and personalization, this layout is by no means a presciptive one size fits all solution, but rather a basis for users to start out and play around with. It's also an artifact to convince people that 4x10 ortholinear boards are very much viable<sup>1</sup> for actual office work and use (minus anything that needs a dedicated keypad).

## General Principles
- Should strive to be relatively easy to learn
  - As such, the layout should pull cues from the Planck layout, which generally has symbols in a logical spot coming from a 60%+ keyboard
- Should _not_ be prone to destructive/disruptive mispresses
  - No home row mod keys<sup>2</sup>, and keys that can send message like `Enter` should be a fair distance away
- Should _never_ require hotkey changes in the software/OS that you use
  - I don't like the idea of unnecessarily changing settings on your computer to accomodate your keyboard, since said settings won't apply to other computers
- Strive for general ortholinear keyboard "ergonomics" when possible

## Featues
- Uses QWERTY (Optional)
  - No additional time required to learn a new typing scheme
  - Makes it easier to use shortcuts like `Ctrl`+{`Z`,`X`,`C`,`V`,`F`,...}
    - QMK shortcuts like Copy, Paste, Etc. exist, but do not cover ALL possible shortcuts
- Puts Arrow Keys on `H`,`J`,`K`, and `L` on the Raise layer
  - Nicely matches VIM navigation
  - Pretty comfortable 
  - Only requires one hand (so the other can drink coffee and scratch chin)
- Have layer/`Shift`/`Control` keys spanning only 4 keys
  - Having 6 layer keys like Miryoku isn't super comfortable on an ortholinear, as I found that I had to really strech my thumbs in to hit the outer most thumb keys
- Use [ModTap](https://github.com/qmk/qmk_firmware/blob/master/docs/mod_tap.md) on thumb keys only
  - very hard to misfire/mistime accidental mods
- Enter and Escape key are intentionally on the far corners of the bar to prevent getting hit by any thumb mispresses

________________________________
1. The irony of describing the layout as "viable" rather than "optimal" or "better" is not lost out on me :)
2. There's nothing wrong with home row mods per se. It's just when I was learning with it, I was accidentally firing off modifiers which would alter my UI/Close programs/Send messages that weren't ready to be sent/etc. I could learn to press lighter on the keys or adjust timing values, but I was way too frustrated at that point, and don't like the idea that there could always be a slim chance that I could misfire one them off. If it's your cup of tea, kudos
