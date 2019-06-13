# 12th June
This file includes notes and materials for the third day of the course and will grow during the day.
## What we cover today
  
### Introduction to stylometry
* Verifying hypotheses with networks case study: Doctor Who
* Networks in Gephi - how to
* Community detection methods, such as Leuven modularity algorithm
  * Modularity algorithm
    * Is one of *community detection* algorithms.
    * Modularity has a high value when many more edges in a network fall between vertices of the same type then one would expect by chance,
    * Good divisions of the network into communities are those that have high values of the corresponding modularity.
  * Community detection:
    * the search for the naturally occurring groups in a network regardless of their number or size,
    * used primarily as a tool for discovering and understanding the large-scale structure of networks.
    * separates network into groups of vertices that have few connections between them.
* Writing simple R scripts
* How to compare corpora? How to divide corpus into representative samples?
* Craig's Zeta and its implementation in oppose() function of 'stylo' package:
  * words preferred - words consistently used only in the primary set,
  * words avoided - words consistently used only in the secondary set,
  * markers.
* [slides on Craig's Zeta](https://github.com/JoannaBy/DHSI2019-Stylometry/blob/master/presentations/Comparing%20(groups%20of)%20texts.pdf) - the part of my research removed as it is currently under peer review

### New functions
```
oppose()  
```
a function performing a contrastive analysis. You need *primary_set* and *secondary_set* in your *A_Small_Collection* folder. In each folder we put a number of texts representing a group suspected of being distinctive from the other one in a significant way. 

### The reading
#### From the coursepack
* Craig, H., and Kinney, A. F. “Methods.” in Shakespeare, Computers, and the Mystery of Authorship, Cambridge University Press, 2009, p. 15-40.
* Burrows, J. “All the Way Through: Testing for Authorship in Different Frequency Strata.” Literary and Linguistic Computing, vol. 22, no. 1, Apr. 2007, pp. 27–47.
* Hoover, D. L. “Teasing Out Authorship and Style with T-Tests and Zeta”. DH2010 Book of Abstracts.

#### From the coursepack - documentation of functions we use today:
* [Short reminder](https://computationalstylistics.github.io/stylo_nutshell/#running-oppose)
* Eder, M., Kestemont, M. and Rybicki, J. ‘Stylo’: a package for stylometric analyses (a manual). 2015. [Click.](https://sites.google.com/site/computationalstylistics/stylo/stylo_howto.pdf?attredirects=1) - pages 26-27.
* [CRAN documentation](https://cran.r-project.org/web/packages/stylo/stylo.pdf) - pages 39-41.
* Eder, M., Kestemont, M. and Rybicki, J. “Stylometry with R: A Package for Computational Text Analysis.” The R Journal, vol. 8, no. 1, 2016, pp. 107–21. [Click.](https://journal.r-project.org/archive/2016/RJ-2016-007/RJ-2016-007.pdf) 

### Regular expressions aka regex
Regex for extracting author (or rather: all the letters before a first non-character sign appears, so everything before first underscore): ^[A-Za-z]*  
Regex for extracting text after the first underscore (but befor another non-character sign appears): \_[A-Za-z]*
  
Learn more:
* [Regex cheatsheet](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
* [Get regex skills doing crosswords!](https://regexcrossword.com/) - by far the coolest way to learn regex.  
* [Regex sandbox](https://regex101.com/) - this is where you can test your regex.  


#### Extras
* Six degrees of Kevin Bacon [Exploration](http://www.sixdegreesoffrancisbacon.com/?ids=10000473&min_confidence=60&type=network), [wiki](https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon)
* Jan Rybicki's paper on gender differences:  
Rybicki, J. “Vive La Différence: Tracing the (Authorial) Gender Signal by Multivariate Analysis of Word Frequencies.” Digital Scholarship in the Humanities, vol. 31, no. 4, Dec. 2016, pp. 746–61, doi:10.1093/llc/fqv023.
* Detailed insight into comparing corpora:  
Kilgarriff, Adam. “Comparing Corpora. International Journal of Corpus Linguistics, vol. 6, no. 1, 2001, pp. 97–133.
* Best introduction to networks - Mark Newman, Networks: An Introduction.



