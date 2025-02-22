# Spacemak
Spacemak is a universal keyboard layer concept and fully compatible with any alphanumeric / language layout. It offers a navigation, shortcut and editing layer and an additional symbol (or optional number or mouse) layer. The Shift-function is made easier to access than on a standard keyboard layout as well. Finally on the lower row, bottom-row mods are implemented for easy access of key-combo's with Ctrl and other modifiers.

Spacemak is an alternative to the even more comfortable [Anymak](https://github.com/rpnfan/Anymak) concept. Advantage of Spacemak is that no changes to the used alphanumeric layout are needed.

Spacemak offers a huge gain in keyboard productivity and comfort. There is simply no serious reason not us use — at least to implement it partially. Here an example implementation for QWERTY on a split ergonomic keyboard. The concept can be applied in exactly the same way on a standard keyboard. Read a detailed article on kbd.news, explaining the Anymak and Spacemak concept: https://kbd.news/Anymak-the-compatible-ergonomic-keyboard-layout-2574.html

## Building blocks of Spacemak
Spacemak combines the following 
1. [SpaceFN concept](https://kbd.news/The-SpaceFN-concept-2315.html) 
2. [hold-tap](https://zmk.dev/docs/keymaps/behaviors/hold-tap) to access the shift- and additional symbol layer
3. [bottom-row-mods](https://precondition.github.io/home-row-mods#upperlower-row-mods)

![image](https://github.com/user-attachments/assets/10ef03da-93ff-4422-9ab7-4da0393ea4c7)

## Shift and symbol layer
Shift and symbol layer are accessed by hold-tap functions. Both Shift and the symbol layer keys are set-up symmetrical, see the graphic above.
The symbol layer can be populated with symbols you want to access easier, including those which are normally not directly available, such as greek characters, math symbols, typographic sugar (no-break space and others).

## Navigation and shortcut layer
The navigation layer is accessed by keeping the Space-key held with the thumb on the opposing hand. My navigation layer looks like that.
![image](https://github.com/user-attachments/assets/843f1295-9453-4ff6-b977-bb3db8921ebf)

## Hardware or software implementation
Spacemak can either be realized with a programmable keyboard. For a split standard keyboard I had great success with the UHK 60 v2. But any keyboard supporting QMK, ZMK or other ways to program your keyboard will work. To use Spacemak on a laptop or with a standard keyboard I suggest to use Kanata, which is available for Windows, Linux and macOS.




