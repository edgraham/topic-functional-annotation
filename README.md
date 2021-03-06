# TOPIC: Functional Annotation
A repository for the lessons and tutorials for the Functional Annotation TOPIC channel of the [BVCN](https://biovcnet.github.io/)


## Prerequisites
* [A working Unix environment](https://github.com/biovcnet/biovcnet.github.io/wiki/1.-Setting-up-a-local-Linux-(or-Unix)-environment)
* [Experience with the command line](https://github.com/biovcnet/biovcnet.github.io/wiki/2.-Using-the-Command-line)

# Overview
This BVCN topic will cover:

* how to predict opening reading frames for all three domains of life
* the methodologies used to assign functions to proteins
* the intricacies of the specific tools and databases that can used for varying levels of specificity

# Lessons
## Lesson 1 -- How to predict open reading frames on DNA
### Introductory material
Date posted: 9 April 2020  
Author(s): Dr. Benjamin Tully  
Instructor(s): Dr. Benjamin Tully  
* Tools for predicting open reading frames for Bacteria and Archaea
* Tools for predicting open reading frames for Eukaryotes
* Converting open reading frames to predicted proteins

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-1/Lesson-1.pdf) | [Video presentation](https://youtu.be/uGjjN-q7N2E)
### Interactive material
Date posted: 9 April 2020  
Author(s): Dr. Benjamin Tully  
Instructor(s): Dr. Benjamin Tully  
* Use Prodigal to predict microbial proteins

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-1/README.md) | [Video presentation](https://youtu.be/on2fZveY8sU) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/biovcnet/topic-functional-annotation/master?urlpath=lab)

Primary tools/programs used:
 * [Prodigal](https://github.com/hyattpd/Prodigal)
 * [GeneMarkS-2](http://exon.gatech.edu/GeneMark/index.html)
 * [Braker](https://github.com/Gaius-Augustus/BRAKER)
 * [Maker](http://www.yandell-lab.org/software/maker.html)

---

## Lesson 2 -- Inferring function from homologous matches
### Introductory material
Date posted: 18 April 2020  
Author(s): Dr. Benjamin Tully  
Instructor(s): Dr. Benjamin Tully  
* Difference between homolog and ortholog?
* Tools for homology based functional annotation

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-2/Lesson-2.pdf) | [Video presentation](https://youtu.be/sOFoytKXrHA)

### Interactive material
Date posted: 9 April 2020  
Author(s): Dr. Benjamin Tully  
Instructor(s): Dr. Benjamin Tully  
* Use BLAST+ and DIAMOND
* Interpret similarity based results  

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-2/README.md) | [Video presentation](https://youtu.be/u81xc86ifM8) | [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/biovcnet/functional-annotation-lesson-2-binder/master?urlpath=lab)  

Primary tools/programs used:
 * [BLAST+](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastDocs&DOC_TYPE=Download)
 * [DIAMOND](https://github.com/bbuchfink/diamond)

---

## Lesson 3 -- Function from position-sensitive models
### Introductory material
Date posted: 1 May 2020  
Author(s): Dr. Benjamin Tully, Dr. Adelaide Rhodes  
Instructor(s): Dr. Benjamin Tully  
* How do position-sensitive models work?
* How to use a position-sensitive model to interpret function

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-3/Lesson-3.pdf) | [Video presentation](https://youtu.be/sIqPpmadiRg)

### Interactive material
Date posted: 1 May 2020  
Author(s): Dr. Benjamin Tully, Dr. Adelaide Rhodes  
Instructor(s): Dr. Benjamin Tully  
* Use HMMER
* Interpret HMM search results  

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-3/README.md) | [Video presentation](https://youtu.be/sbDjLR0LvjU) | [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/biovcnet/functional-annotation-lesson-3-binder/master?urlpath=lab)  

Primary tools/programs used:
 * [HMMER](http://hmmer.org/)

---

## Lesson 4 -- HMM-based annotation - FeGene Introduction 
### Introductory material
Date posted: 5 May 2020   
Author(s): Arkadiy Garber   
Instructor(s): Arkadiy Garber   
* Describe the process for making HMM to detected iron-related proteins
* How FeGenie works

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-4/FeGenie%20intro%20and%20tutorial.pdf) | [Video presentation](https://www.youtube.com/watch?v=sp5ZDcHaYOc)

### Interactive material
Date posted: 5 May 2020   
Author(s): Arkadiy Garber   
Instructor(s): Arkadiy Garber   
* Demonstration of how FeGenie identifies iron-related proteins

[Content](https://github.com/biovcnet/topic-functional-annotation/blob/master/Lesson-4/README.md) | [Video presentation](https://www.youtube.com/watch?v=WV0GAGSD4kc) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Arkadiy-Garber/bvcn-binder-FeGenie/master?urlpath=lab)  

Primary tools/programs used:
 * [FeGenie](https://github.com/Arkadiy-Garber/FeGenie)
    * [Citation](https://www.frontiersin.org/articles/10.3389/fmicb.2020.00037/full)

