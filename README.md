# LING 490 Capstone: CT Realizations in Attention Patterns for Chinese Zero Anaphora Resolution

This project aims to investigate 
1) whether Chinese zero anaphora resolution according to several proposed instantiations of [Centering Theory](https://aclanthology.org/J95-2003.pdf) (Grosz et al.) is realized in multi-head attention networks
2) where this realization occurs in the network

transitions.ipynb: 
* converts OntoNotes documents into usable components for retrieving indices of relevant tokens
* compares attention patterns in selected heads/layers of given model to Cf rankings
Implementation details can be found within the file.

sentence_piece.ipynb:
* trains a sentence piece tokenizer for whole-word segmentation of Chinese text on held-out portions of the OntoNotes datasets.

visual_analysis.ipynb (TBD):
* compares the alignment of CT instantiations to attention patterns. 
* compares the performance of CT instantiations in resolving zero-anaphora
* generates visualizations of comparisons

Data:
This project utilizes version 5.0 of the [OntoNotes dataset](https://catalog.ldc.upenn.edu/LDC2013T19) released by the Linguistic Data Consortium

Paper: 
The paper for this project can be found here [Exploring the Expression of Centering Theory Instantiations in
Transformer-based LMs](https://www.overleaf.com/read/jcnwmqhqwgdb#086bd0)


