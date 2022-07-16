[![Version](https://vsmarketplacebadge.apphb.com/version/jock.svg.svg)](https://marketplace.visualstudio.com/items?itemName=jock.svg)

# svg

A Powerful SVG Language Support Extension.
Almost all the features you need to handle SVG.

## Caution

**There have been multiple reports that the minimization feature may break your SVG, and we are still looking for a better library replacement for SVGO, so back up your SVG documentation when using the minimize feature.**

## Features

### SVG Full Auto Completion

![feature 1](images/f1s.gif)

> Tip: All Completion list is context, will only show enable items.

### Document Symbol tree

![feature 2](images/f3.png)

### SVG Live Preview and Export PNG

![feature 3](images/f2s.gif)

### MDN Reference for fast learn

![feature 4](images/f3s.gif)

> Tip: Configure Trusted Domains add MDN to it get more fast action.

### Fast Color Picker

![feature 4](images/f4s.gif)

### Rename Tag Name or Id Reference

Cursor in Tag Name or Id Attribute or url(#id) Hit F2(Windows) Key, Rename it!

### In Id Reference Click Goto id="" element

Hot Ctrl Key and Move mouse to a url(#id), That it!

### SVG Format Support

Default formatting support is HTML Language Serivce for compatible with complex svg content

### Minify SVG with SVGO

Open the **Command Palette** (`⇧⌘P` on Mac and `Ctrl+Shift+P` on Win/Linux) and run `Minify SVG`. This will reduce the filesize significantly by removing all unnecessary code from the image.

## Contributors

* [Laurent Tréguier](https://github.com/LaurentTreguier) for sharing SVG formatting features
* [Björn Ganslandt](https://github.com/Ansimorph) for sharing Minify SVG features
* [Amelia Bellamy-Royds](https://github.com/AmeliaBR) for Add the xmlns and xmlns:xlink attributes
* [Evan Demaris](https://github.com/evandemaris)
* [Trevor Burnham](https://github.com/TrevorBurnham)
* [Philipp Kief](https://github.com/PKief)
* [rioj7](https://github.com/rioj7)

## Known Issues

SVG Version 2.0 is not included.

## Changelog

### 1.4.19 - 2022-07-16

* Part support CDATA in script/style element.
* Add `Preview All: Exclude` Configure for `Preview All Svg` command filter files.

### 1.4.18 - 2022-05-14

* Preview zoom level will not reset when document change.

### 1.4.17 - 2022-02-09

* Preview min Zoom will auto change for big size svg.

### 1.4.16 - 2022-02-05

* Add `Translate External Address` Setting for Show `<img>` mode external url content

### 1.4.15 - 2021-12-22

* Fix Previewr Focus Unexception.
* Add Warring for `Minify`.
* Add `Code Interactive` Button in Preview toolbar.

### [MORE](Changelog.md)

## Donations

[Support me in paypal](https://www.paypal.me/jockli).

-----------------------------------------------------------------------------------------------------------

## For more information

* [MDN SVG Reference](https://developer.mozilla.org/en-US/docs/Web/SVG)

**Enjoy!**
