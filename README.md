sublime-gff3
============

Sublime Text GFF3 syntax definitions for the Generic Feature Format, version 3 (GFF3) as defined by the [specification](http://www.sequenceontology.org/gff3.shtml). 
Formats the syntax of the following elements of a GFF3 file:

- meta lines (`##sequence-region`,`##gff-version` etc.)
- comments (`#foo bar`)
- numbers/ranges
- attribute-value pairs (`foo=bar;`)
- reserved attributes like `ID`, `Parent`, `Derives_from`, `Target`…
- terminators (`###`) 

It also forces tabs to be used regardless of the general user preference, so a valid GFF file can be created even by users who usually prefer spaces instead of tabs (like I do).

![Example](https://raw.githubusercontent.com/satta/sublime-gff3/master/screen.png)

## Installing

**Manually:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `GFF3`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text 2.

**Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/satta/sublime-gff3.git

## Usage
Once installed, use the menu (View->Syntax->GFF3) to apply the syntax highlighting to the currently opened document. The syntax definition will automatically be applied to `.gff` and `.gff3` files.