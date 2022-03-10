# CUBCO+

### CUBCO+: Prediction of protein complexes based on min-cut network partitioning into biclique spanned subgraphs 

High-throughput proteomics approaches have resulted in large-scale protein-protein interaction (PPI) networks that have been employed for the prediction of protein complexes. However, PPI networks contain false-positive as well as false-negative PPIs that affect the protein complex prediction algorithms. To address this issue, here we propose an algorithm called CUBCO+ that: (1) employs GO semantic similarity to retain only biologically relevant interactions with high similarity score, (2) based on link prediction approaches, scores the false-negative edges, and (3) incorporates the resulting scores to predict protein complexes. Through comprehensive analyses with PPIs from Escherichia coli, Saccharomyces cerevisiae, and Homo sapiens, we show that CUBCO+ performs as well as the approaches that predict protein complexes based on recently introduced graph partitions into biclique spanned subgraphs and outperforms the other state-of-the-art approaches. Moreover, we illustrate that in combination with GO semantic similarity, CUBCO+ enables us to predict more accurate protein complexes in ~36% of the cases in comparison to CUBCO as its predecessor. 


The PPI networks and implementation of CUBCO+ with an example is available in a separate Jupyter notebook.
