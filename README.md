# Sci-k2021

## Doc1 description
Doc1 is a report YF wrote for a class project during which the rhetorical classifers were built. It included details on:  
(1) testing different classifers (Naive Bayes, SVM, and decision tree)   
(2) testing two representation strategies: bag-of-words and trigram  

## Doc2 description
Doc2 included the 99 citation context sentences citing the willoughby-hoye protocol [1] (downloaded from scite.ai and manually cleaned), their rhetorical category classifications, and keystone citation annotation (by YF) of the 43 sentences that recieved a positive classification.  

Explanation of the column headings  
  
**SENTID**.: assigned sentence id by scite.ai  
**SENTENCE**: sentences that contains the citation of the the willoughby-hoye protocol. Notice the xml tags for the citations and the citation string (e.g., 23, [10]) have been removed to not confuse the classifiers, which was trained on abstract sentences that often do not contain citations. YF plan to fill in the original sentences in the future, with the XML tags and citation string.  
**BACKGROUND_CLASSIFIER_PREDICTION**: classfication results of the Background classifer  
**OJBECTIVE_CLASSIFIER_PREDICTION**: classfication results of the Objective classifer  
**METHODS_CLASSIFIER_PREDICTION**: classfication results of the Methods classifer  
**RESULTS_CLASSIFIER_PREDICTION**: classfication results of the Results classifer  
**CONCLUSIONS_CLASSIFIER_PREDICTION**: classfication results of the Conclusions classifer  
**SECTION_HEADING**: headings of the section in the paper where the sentences were found
**YF KEYSTONE ANNOTATION**: KEYSTONE CITATION or NOT KEYTSTONE CITATION, annotated by YF for the 43 sentences with positive rhetorical category classifications
**NOTE**: notes comes with the KEYSTONE ANNOTATION.

[1] Willoughby, P.H., Jansma, M.J. and Hoye, T.R. 2014. A guide to small-molecule structure assignment through computation of ( 1 H and 13 C) NMR chemical shifts. Nature Protocols. 9, 3 (Mar. 2014), 643–660. DOI:https://doi.org/10.1038/nprot.2014.042.
