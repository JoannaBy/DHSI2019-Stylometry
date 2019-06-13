# 13th June
This file includes notes and materials for the fourth day of the course and will grow during the day.
## What we cover today?
  
### Introduction to stylometry
* What is classification? How does it work?
  * Training set vs test set
  * Training the classifier
  * Cross-validation
  * Conditions of a reliable classification study - how to choose texts? how many words do we need?
* Supervised classification with classify()
* Taking a closer look at the author - sequential analysis with rolling.classify()

### New functions
```
classify()
````
a function performing classification.  
  
Data setup:  
You need *primary_set* and *secondary_set* in your *A_Small_Collection* folder.  
*Primary_set* serves as a training set, and *secondary_set* is where we put texts to be tested, which means that texts in the *primary_set* will be used to create a virtual model of style for each class of the texts (class is indicated by information before the underscore in the name of the file, e.g. for Austen_Emma.txt class would be Austen).  
After training the model, the texts in the *secondary_set* will be compared to it, based on which a classification is made - which class seems to be the one our tested text fits best.
  
**How to put results of classification in a variable**
```
results = classify(cv.folds = 10)
```

### The reading
#### From the coursepack
* Burrows, J. “‘Delta’: A Measure of Stylistic Difference and a Guide to Likely Authorship.” Literary and Linguistic Computing, vol. 17, no. 3, Sept. 2002, pp. 267–87.  
* Eder, M. “Rolling Stylometry.” Digital Scholarship in the Humanities, vol. 31, no. 3, Sept. 2016, pp. 457–69. 
#### Extra - texts on culling
* Hoover, D.L. [Testing Burrows's Delta](https://academic.oup.com/dsh/article-abstract/19/4/453/943644?redirectedFrom=fulltext)
* Hoover, D.L. [Delta Prime?](https://academic.oup.com/dsh/article-abstract/19/4/477/943645?redirectedFrom=fulltext)

#### From the coursepack - documentation of functions we use today:
* [Short reminder](https://computationalstylistics.github.io/stylo_nutshell/#running-rolling.classify)
* Eder, M., Kestemont, M. and Rybicki, J. ‘Stylo’: a package for stylometric analyses (a manual). 2015. [Click.](https://sites.google.com/site/computationalstylistics/stylo/stylo_howto.pdf?attredirects=1) - pages .
* [CRAN documentation](https://cran.r-project.org/web/packages/stylo/stylo.pdf)
* Eder, M., Kestemont, M. and Rybicki, J. “Stylometry with R: A Package for Computational Text Analysis.” The R Journal, vol. 8, no. 1, 2016, pp. 107–21. [Click.](https://journal.r-project.org/archive/2016/RJ-2016-007/RJ-2016-007.pdf) 

#### Extras
[Maciej's paper on short samples in authorship attribution](https://dh2017.adho.org/abstracts/341/341.pdf)
[Cross-validation using the function classify](https://computationalstylistics.github.io/docs/cross_validation)  
[Rolling stylometry](https://computationalstylistics.github.io/docs/rolling_stylometry)  
[Using custom distance measures](https://computationalstylistics.github.io/docs/custom_distances)
