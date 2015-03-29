# Varicolor

Colorful and Generic Syntax Highlighting. Suitable for most imperative programming languages.

---
This repository contains a syntax definition and a color theme for use with Sublime Text and pretty much any language that looks anything like C, and it probably looks acceptable on JavaScript and CoffeeScript, too. Imperative.tmLanguage works with other color schemes, but it contains special regex captures that reference additional colors in Varicolor.tmTheme. This allows for more specific language features to have their own colors, and also allows for... more _involved_ structures (read: silly, gaudy things that border on being in really bad taste) like gradients in class and function definitions, and brackets that get darker as they nest deeper.

---
There's also a YAML version of Imperative which is easier to read and edit. I use AAAPackageDev to convert it into the plist format Sublime Text reads. There are some Unity3D / C# specific regexes in Imperative, but I usually disable them before I commit. If you use Unity, and you want some cool IDE highlighting, you can turn them back on by uncommenting their #include statements in the YAML file.

---
Todo: 
- Figure out how to make this available on Package Control
- Add some snippets / completions for ubiquitous things, functions and while loops, _et cetera_
- There's probably some work to be done to make this compatible with other people's MFTLs

---
These screenshots show Inconsolata-dz, which is a particularly tasty programming font. 
![](https://github.com/iasEnvy/varicolor/blob/master/Screenshots/c-example.png)
![](https://github.com/iasEnvy/varicolor/blob/master/Screenshots/c-sharp-example.png)
