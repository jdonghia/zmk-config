# ZMK Config

Personal ZMK user configuration for a Corne split keyboard. This repo includes the keymap, Kconfig settings, and the West manifest that pins the ZMK version used in CI builds.

## Keyboard Layout Diagrams

### Default Layer

```
// -----------------------------------------------------------------------------------------
// |  TAB |  Q  |  W  |  E  |  R  |  T  |   |  Y  |  U   |  I  |  O  |  P  | BSPC |
// | CTRL |  A  |  S  |  D  |  F  |  G  |   |  H  |  J   |  K  |  L  |  ;  |  '   |
// | SHFT |  Z  |  X  |  C  |  V  |  B  |   |  N  |  M   |  ,  |  .  |  /  | ESC  |
//                    | GUI | LWR | SPC |   | ENT | RSE  | ALT |
```

### Lower Layer

```
// -----------------------------------------------------------------------------------------
// |     |  1  |  2  |  3  |  4  |  5  |   |  6  |  7  |  8  |  9  |  0  |     |
// |     |  ;  |     |     |  `  |     |   |     |     |     |  [  |  ]  |     |
// |     |     |     |     |     |     |   |  \  |  -  |  =  |  <  |  >  |     |
//                    |     |     |     |   |     |     |     |
```

### Raise Layer

```
// -----------------------------------------------------------------------------------------
// |     |  F1 |  F2 |  F3 |  F4 |  F5 |   |  F6 |  F7 |  F8 |  F9 | F10 |     |
// |     | F11 | F12 |     |     |     |   | LFT | DWN |  UP | RGT |     |     |
// |     |     |     |     | BT_NXT | BT_CLR |   |     |     |     |     | BOOT |
//                    |     |     |     |   |     |     |     |
```

## Layers

- Default: alphas and core modifiers
- Lower: numbers and symbols
- Raise: function keys, arrows, and Bluetooth/bootloader actions

