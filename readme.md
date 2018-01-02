This repository contains the code for extracting concept ontology from Wikipedia.

The processed data can be downloaded from [Google Drive](https://drive.google.com/open?id=1Z1ImLo7BIEka5_5K3DFsgQBcxR4bpMz3).

The processed data are:

1. `concept_ontology.nx.pickle`. `NetworkX` directed graph file. The edge points from a finer concept to a general concept. This is converted from the Wikipedia category network and does not contain any Wikipedia pages.
2. `concept_ontology.edgelist`. Plaintext version of `concept_ontology.nx.pickle`
3. `page_category.txt.gz`. A three-column space separated file. The first column is the concept or its surface form, the second column is the concept category in the NetworkX that contains such concept. The third column is used to match original Wikipedia page ids. 