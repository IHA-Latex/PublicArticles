# Public articles

When you want to write an article it must be done with the APA-6 style, read more [here](http://www.apastyle.org/).
This is a Latex template for writing public articles in APA-6 style.

For the APA-6 style you must use the ```\documentclass[jou]{apa6}```.
This will format your article in 2 columns, give the correct formating of the abstract, authors and so on.

## Commands to know
The APA-6 style's documentation can be found [here](http://www.ctan.org/pkg/apa6).

The most important are listed below:

* ```\abstract{Long text here}``` - Preamble
* ```\title{Long title of publication}``` - Preamble
* ```\shorttitle{Short title for header}``` - Preamble
* ```\author{Author1 and Author2}``` - Preamble. Notice this is only from your own institute (see documentation for multiple institutes).
* ```\affiliation{Your university}``` - Preamble
* ```\leftheader{Last name of authors}```  - Preamble (optional)
* ```\abstract{Long abstract of your article}``` - Preamble
* ```\keywords{keywords, listed, commas seperated}```  - Preamble (optional)

## The structure

When organizing your files, you can use the following structure:
+ Documents/
  + Assignment/
    - As1.tex
    - As2.tex
    - Main.tex
    - Preamble.tex
    - ...
  + Figures/
    - Dummy.png
    - ...
  + LatexModules
    - Apa6.tex
    - *.tex
    - ...
