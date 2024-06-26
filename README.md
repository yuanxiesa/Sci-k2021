# Sci-k2021

This repository contains supplyement material for my Sci-k2021 paper  
Yuanxi Fu, Jodi Schneider, and Catherine Blake, 2021. Finding keystone citations for constructing validity chains among research papers. In Companion Proceedings of the Web Conference 2021. DOI: https://doi.org/10.1145/3442442.3451368

## Doc1 description
Doc1 is a report YF wrote for a class project during which the rhetorical classifers were built. It included details on:  
(1) testing different classifers (Naive Bayes, SVM, and decision tree)   
(2) testing two representation strategies: bag-of-words and trigram  

## Doc2 description
Doc2 included the 99 citation context sentences citing the willoughby-hoye protocol [1] (downloaded from scite.ai and manually cleaned), their rhetorical category classifications, and keystone citation annotation (by YF) of the 43 sentences that recieved a positive classification.  

### Explanation of the column headings  
  
**SENTID**.: assigned sentence id by scite.ai  

**SENTENCE**: sentences that contains the citation of the the willoughby-hoye protocol. Notice the xml tags for the citations and the citation string (e.g., 23, [10]) have been removed to not confuse the classifiers, which was trained on abstract sentences that often do not contain citations.  

**SENTENCE_WITH_XML**: sentences with XML tags and citation strings.  

**BACKGROUND_CLASSIFIER_PREDICTION**: classfication results of the Background classifer  

**OJBECTIVE_CLASSIFIER_PREDICTION**: classfication results of the Objective classifer  

**METHODS_CLASSIFIER_PREDICTION**: classfication results of the Methods classifer  

**RESULTS_CLASSIFIER_PREDICTION**: classfication results of the Results classifer  

**CONCLUSIONS_CLASSIFIER_PREDICTION**: classfication results of the Conclusions classifer  

**SECTION_HEADING**: headings of the section in the paper where the sentences were found  

**HIT(1-HAS POSITIVE CLASSIFICATION/0-NO POSITIVE CLASSIFICATION)**: whether there is a positive classification from RC classifiers  

**RC_CLASSIFICATION**: RC classifications (condensed)  

**YF KEYSTONE ANNOTATION**: METHODS KEYSTONE or NOT METHODS KEYTSTONE, annotated by YF for the 43 sentences with positive rhetorical category classifications  

**NOTE**: notes comes with the KEYSTONE ANNOTATION.  

[1] Willoughby, P.H., Jansma, M.J. and Hoye, T.R. 2014. A guide to small-molecule structure assignment through computation of ( 1 H and 13 C) NMR chemical shifts. Nature Protocols. 9, 3 (Mar. 2014), 643–660. DOI: https://doi.org/10.1038/nprot.2014.042.
