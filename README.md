
# Spacemak

Spacemak is a universal keyboard layer concept, fully compatible with any alphanumeric or language layout. It offers a navigation, shortcut and editing layer, plus an additional symbol layer (optionally a number or mouse layer). Shift is made easier to access than on a standard keyboard, and on the lower row, bottom-row mods are implemented for convenient access to key combos with Ctrl and other modifiers.

Spacemak is the light option of the even more comfortable [Anymak](https://github.com/rpnfan/Anymak) concept, for those who want to keep their existing alphanumeric layout unchanged. A good entry point if you want most of the navigation and shortcut benefits with minimal disruption to your current setup. Choose the concept which makes most sense for you.

Spacemak offers a huge gain in keyboard productivity and comfort. There is simply no good reason not to try it — even a partial implementation brings real benefits. Below is an example implementation for QWERTY on a split ergonomic keyboard. The concept applies in exactly the same way on a standard keyboard. For a detailed explanation of the Anymak and Spacemak concepts, see the article on kbd.news: https://kbd.news/Anymak-the-compatible-ergonomic-keyboard-layout-2574.html

## Building blocks of Spacemak

Spacemak combines the following:

1. [SpaceFN concept](https://kbd.news/The-SpaceFN-concept-2315.html) — the Space key doubles as a layer-shift when held, enabling a full navigation layer under the right hand
2. [Hold-tap](https://zmk.dev/docs/keymaps/behaviors/hold-tap) — used to access the Shift and additional symbol layer from thumb or pinky keys
3. [Bottom-row mods](https://precondition.github.io/home-row-mods#upperlower-row-mods) — modifier keys on the bottom row for easy one-handed shortcuts
4. CapsLock-key as a modifier — access to an additional (right-hand) symbol layer

![image](https://github.com/user-attachments/assets/10ef03da-93ff-4422-9ab7-4da0393ea4c7)

## Shift and symbol layer

Shift and the symbol layer are accessed via hold-tap functions. Both are set up symmetrically — see the graphic above (green and red color coded keys). 

The symbol layer can be populated with whatever symbols you want easier access to, including those not directly available on a standard layout, such as Greek characters, math symbols, and typographic extras like the non-breaking space. Or you can use it for a number pad or mouse layer.

## Navigation and shortcut layer

The navigation layer is activated by holding the Space key with the thumb on the opposing hand. Here is an example of what that layer can look like:

![image](https://github.com/user-attachments/assets/843f1295-9453-4ff6-b977-bb3db8921ebf)

## Hardware or software implementation

Spacemak can be realized either with a programmable keyboard or through software. For a split keyboard, the UHK 60 v2 works very well, but any keyboard supporting QMK, ZMK or similar firmware will do. To use Spacemak on a laptop or standard keyboard, [Kanata](https://github.com/jtroo/kanata) is a great option — available for Windows, Linux and macOS. Under releases you find an [example Kanata config](../../releases) you can use as a starting point. It is not fully configured, because different people will adapt it to their indidivual needs and wishes.

## Keyboard layout compatibility

Spacemak works with any keyboard layout: QWERTY, Colemak, Dvorak and so on. If you want to squeeze out the last bit of typing comfort, learning an alternative layout may be worth it. In that case, [Anymak](https://github.com/rpnfan/Anymak) is fully optimized for comfort, including shift and symbol layer key placement. If you prefer a layout that only optimizes character positions without changing how Shift works, you might find the En* keyboard layouts interesting — available for English, German [EnDeu](https://github.com/rpnfan/EnDeu), and other language combinations including Dutch, French and Spanish. This is the perfect companion alphanumeric layer for Spacemak.
