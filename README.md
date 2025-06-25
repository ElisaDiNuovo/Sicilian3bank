# Sicilian3bank
This repository is hosting the first version of the parallel treebank Sicilian-Italian in Universal Dependencies, submitted to CLiC-it 2025, entitled
Arbuli sunnu: a Sicilian-Italian Parallel Treebank (Cappello et al., 2025)

The directory CoNLL-U contains the CoNLL-U files of the parallel treebank. 
The gold file is the manually corrected version of the Sicilian treebank (original language). 
Automatically annotated versions are uploaded too, for these versions we used UDPipe parser and in particular two models trained on two Italian treebanks, i.e. ISDT and PoSTWITA. 
The Italian treebank (translated language), made of 1:1 aligned translated sentences into Italian of the gold segmentated Sicilian texts, is automatically parsed using the same two UDPipe models as the automatically annotated Sicilian counterpart. 

The txt files with gold segmentation are provided for both languages (Sicilian, original, and Italian, translation) in the directory named gold_segmentation.

We also provide the translations with footnotes to provide further details on translation choices.

