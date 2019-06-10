# 11th June

This file includes notes and materials for the first day of the course and will grow during the day.

### Today we covered - introductions to stylometry:
* history of stylometry (early cases of debate over authorshop of The Donation of Constantine, works of Shakespeare, Pauline Epistles and Plato),
* what kind of texts do we need for the analysis? "Raw" texts usually provide enough information for a successful authorship attribution,
* applications of stylometry: authorship attribution, genre studies, chronology studies,
* how does stylometry work?
* why do the most frequent words matter,
* the concept of Delta distance measure,
* cluster analysis - simple classification supervised machine learning method,
* bootstrap consensus tree (more on that tomorrow!)
* R as a programming language - how to move in command line, function (an action performed to achieve some defined result) vs variable (place you store something)

### In stylo
#### Set the working directory:

Command line: 
'''
setwd("the/path/to/my/favourite/folder")
'''

RStudio users: find your directory in the Files panel, then use Menu > More > Set as Working Directory

Windows users: use Menu > File > Change directory

#### New commands
library(stylo) - telling the computer to load 'stylo' library. You need to do this every time you turn on R.
stylo() - command for basic analysis

[cheatsheet docu](https://github.com/JoannaBy/stylo_nutshell)


### The reading behind that (two first texts are in your coursepack):
* Rybicki, J., Eder, M., Hoover, D. L. "Computational Stylistics and Text Analysis." in Doing Digital Humanities. Practice, Training, Research. Eds Crompton, C., Lane, R.J., Siemens, R. Oxford: Routledge, 2016, pp. 123-144.
* Jockers, M. L. “Part I: Foundation.” in Macroanalysis. Digital Methods and Literary History., University of Illinois Press, 2013, pp. 1-32.
* Hoover, D. L. “Quantitative Analysis and Literary Studies.” A Companion to Digital Literary Studies, edited by Ray Siemens and Susan Schreibman, Blackwell, 2008 [online version](http://digitalhumanities.org:3030/companion/view?docId=blackwell/9781405148641/9781405148641.xml&chunk.id=ss1-6-9&toc.depth=1&toc.id=ss1-6-9&brand=9781405148641_brand). 
* Burrows, J. F. Computation into Criticism: A Study of Jane Austen’s Novels and Experiment in Method. Clarendon Press, 1987. *You can find it in UVic's library!*

### Interesting trivia & links
[Telegraph about unmasking Galbraith as Rowling](https://www.telegraph.co.uk/culture/books/10192275/JK-Rowling-unmasked-the-lawyer-the-wife-her-tweet-and-a-furious-author.html)

