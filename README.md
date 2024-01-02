# Iosevka-build
Custom build script for Iosevka font.

## Dependencies
This build script depends on `git`, `nodejs` and `ttfautohint`.

## Differences from the main project
This script only builds `Iosevka-Regular.ttf`, `Iosevka-Bold.ttf`, `Iosevka-BoldItalic.ttf` and `Iosevka-Italic.ttf`.<p>
It enables discretionary ligatures `dlig`, `noCvSs = true`, `exportGlyphNames = true` and changes the font variant of `y -> "cursive-serifless"`, `six -> "closed-contour"`, `nine -> "closed-contour"`.

## Usage
```
$ wget https://raw.githubusercontent.com/teth3r/Iosevka-build/master/iosevka-build
$ chmod +x iosevka-build
$ ./iosevka-build
```
