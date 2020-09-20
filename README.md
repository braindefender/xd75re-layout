# XD75RE Universal Layout

![XD75RE Keyboard](images/Keyboard.JPG)

Universal layout I designed and use on my [XD75RE](https://kprepublic.com/products/xd75re-xd75am-xd75-xiudi-60-custom-keyboard-pcb) ortholinear mechanical keyboard.
The main purpose of this layout is logical positioning of similar symbols altogether.

![Symbot](images/Mascot.png)

##### Key differences from traditional layout:

- Keyboard is split on three parts with Numpad/Arrow block in center.
- All common quotes are placed in one key. Same with slashes and dashes.
- Keys with `, ;` and `. :` are placed separately, right next to `Space` key for each hand.
- Numeric row has been swapped with symbols: to type number use `Shift` + symbol, i.e. `Shift` + `@` = `2`.

## Layer One

![Layer One](images/LayerOne.png)
![Functional Layer One](images/FnLayerOne.png)

## Layer Two

This layer are similar to Layer One, but Numpad is placed on Fn Layer. 
Quotes and slashes are moved closer to the center of keyboard.

![Layer Two](images/LayerTwo.png)
![Functional Layer Two](images/FnLayerTwo.png)


## Alt Layer

Alt Layer contains some symbols for currency, math, arrows and rare letters. 
Keys that combine similar symbols (like quotes and slashes) are also powered by this layer.

![Alternative Layer](images/AltLayer.png)

- 🇷🇺 : Символы `Ё`, `Щ` и `Ъ` помещены на Alt Layer и практически не вызывают проблем в наборе.
- 🇷🇺 : С помощью этого слоя всегда можно ввести символы `[`, `]`, `{` и `}`. 

## Installation

1. Copy `.dll` from `sources` folder to `C:/Windows/System 32`.
2. Then run `.reg` files and reboot the system (or logout / login).
3. Select layout in `Preferences / Language and Region / Language`.
4. [Optional] Rename `HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts` registry entry named `00000409` and `00000419` with something else to prevent Windows 10 from suddenly change layout (Win 10 bug).

## Tools

- Layout design: [Figma](https://www.figma.com), [kbdasm](https://github.com/grompe/kbdasm) and [KbdEdit](http://www.kbdedit.com).
- Firmware: [QMK Configurator](https://config.qmk.fm/#/xd75/LAYOUT_ortho_5x15) to create and [QMK Toolbox](https://github.com/qmk/qmk_toolbox) to flash firmware.


I personally like vim arrows and media shortcuts in Fn Layer. 
`Print Screen` is also very useful for my workflow. 
Take a look at [Flameshot](https://github.com/flameshot-org/flameshot) — it's very good.

