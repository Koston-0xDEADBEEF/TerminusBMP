# TerminusBMP
The original [Terminus](https://terminus-font.sourceforge.net/) bitmap font for macOS systems.

 * Place these to your `~/Library/Fonts` directory.
 * Fonts are available with names `TerminusBMP-Medium` and `TerminusBMP-Bold`

Example configuration for [Alacritty](https://github.com/alacritty/alacritty):

```
font:
  normal:
    family: TerminusBMP-Medium
  bold:
    family: TerminusBMP-Bold
  size: 16
  offset:
    y: -2
```

This is strictly a *bitmap* font, so it will only look good at original sizes:
6x12, 8x14, 8x16, 10x18, 10x20, 11x22, 12x24, 14x28 and 16x32.


Note: Italic version only exists to demonstrate why it shouldn't exist.
