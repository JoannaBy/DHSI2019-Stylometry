# 11th June
This file includes notes and materials for the second day of the course and will grow during the day.
## What we cover today
  * case study "Collaborative authorship in the twelfth century: A stylometric study of Hildegard of Bingen and Guibert of Gembloux"
  * a little about culling [slides](https://joannaby.github.io/Culling/Culling.html)
  * a brief intro to topic modeling
  * methods involving dimension reduction: PCA and MDS, what are their benefits and limitations
  * distance measures in stylometry [slides](https://github.com/JoannaBy/DHSI2019-Stylometry/blob/master/presentations/DistanceMeasures.pdf)
  * bootstrap consensus trees and networks
  
  
### Introduction to stylometry (afternoon plan)
* How are networks useful to literary studies?
* Exploring relations between authors with networks.
  * Collaborative authorship.
  * Stylochronology.
  * Literary big data as a network.  
* Gephi hands on!
  
### The reading
#### From the coursepack - networks and "big" data
* Eder, M. "Does Size Matter? Authorship Attribution, Small Samples, Big Problem." Literary and Linguistic Computing, vol. 30, no. 2, June 2015, pp. 167–82.  
* Rybicki, J., and Eder, M. “Deeper Delta across Genres and Languages: Do We Really Need the Most Frequent Words?” Literary and Linguistic Computing, vol. 26, no. 3, Sept. 2011, pp. 315–21.  
* Eder, M. “Visualization in Stylometry: Cluster Analysis Using Networks.” Digital Scholarship in the Humanities, vol. 32, no. 1, Apr. 2017, pp. 50–64.  

#### Extra reading
* Kestemont et al. "Collaborative authorship in the twelfth century: A stylometric study of Hildegard of Bingen and Guibert of Gembloux", Digital Scholarship in the Humanities 30:2 (2015), pp. 199–224, [here](https://academic.oup.com/dsh/article/30/2/199/389065)
* Waldenfels, R. von, and Eder, M. (2016). A stylometric approach to the study of differences between Croatian and Serbian, or: is the Hobbit in Serbian more Hobbit or more Serbian? Russian Linguistics, 40(1): 11-31, [here](https://www.readcube.com/articles/10.1007%2Fs11185-015-9155-4?author_access_token=iV_8_zTtyav_ifZMovzoAPe4RwlQNchNByi7wbcMAY5cDcal5rddK6Gvy0a6bnmz2ryC6ldf36rLEQY4H3NmrJ6jI-jyvC-H_-RYTrvpf2NXBpudlgy6pyZPuW7DOG9jvTSwDeAx-pcoUMwEKaHVQA==).

#### Extra - texts on culling
* Hoover, D.L. [Testing Burrows's Delta](https://academic.oup.com/dsh/article-abstract/19/4/453/943644?redirectedFrom=fulltext)
* Hoover, D.L. [Delta Prime?](https://academic.oup.com/dsh/article-abstract/19/4/477/943645?redirectedFrom=fulltext)

#### Extra - detailed explanations of dimension reduction methods
* [Making sense of PCA by multistep explanations](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues?answertab=votes#tab-top) - how would you explain it to people with various levels of mathematical understanding, starting with a great-grandmother all the way to a daugther - mathematician.
* [PCA layman video](https://www.youtube.com/watch?v=BfTMmoDFXyE)

#### From the coursepack - documentation of functions we use today:
* [Short reminder](https://computationalstylistics.github.io/stylo_nutshell/#running-stylo)
* Eder, M., Kestemont, M. and Rybicki, J. ‘Stylo’: a package for stylometric analyses (a manual). 2015. [Click.](https://sites.google.com/site/computationalstylistics/stylo/stylo_howto.pdf?attredirects=1) - pages 7-21.
* [CRAN documentation](https://cran.r-project.org/web/packages/stylo/stylo.pdf) - pages 60-66.
* Eder, M., Kestemont, M. and Rybicki, J. “Stylometry with R: A Package for Computational Text Analysis.” The R Journal, vol. 8, no. 1, 2016, pp. 107–21. [Click.](https://journal.r-project.org/archive/2016/RJ-2016-007/RJ-2016-007.pdf) 

### On topic modeling
* [Dariah Topics Explorer](https://dariah-de.github.io/TopicsExplorer/)
* [Programming Historian lesson](https://programminghistorian.org/en/lessons/topic-modeling-and-mallet)
* [R topicmodels package](https://cran.r-project.org/web/packages/topicmodels/index.html) - remember how to install? 
```
install.packages("topicmodels")
```

### Cool trivia
[Mr Darcy in space!](https://archiveofourown.org/works/14296110/chapters/32980422) - many thanks to Tyler for finding this gem!
