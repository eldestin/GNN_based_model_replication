## This repository is the replication of all the GNN-based model I have replicated

### 1. GAT, refer to [@Diego Antognini](https://github.com/Diego999/pyGAT)

GAT structure is the first graph reasoning architecture that I try for my FYP. However, since the computing complexity of attention is too large for a KG, I finally not choose this architecture.

### 2. KG-BERT, refer to [@Weize Chen](https://github.com/thunlp/OpenKE)

This model judge each triple `<head> <relation> <tail> as BERT input with segment ids [0, 1, 0]. I use this model as a basic encoder to extract all infomation from text provided by a KG.`

### 3. Comp-GCN, refer to [@svjan5](https://github.com/malllabiisc/CompGCN)

Comp-GCN with temporal info is used for my FYP. Main difference between this model with GAT is the relation encoding, which provides a direct relationship with dense emebdding. This model is currently used for my FYP task.

### 4. Preprocessing

The data I used here is called YAGO3 KG, which is a multi-relation, multi-lingual KG. All resources can be downloaded [here](https://resources.mpi-inf.mpg.de/yago-naga/yago3.1/).
