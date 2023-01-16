# Compound Classification

For a given compound samples, implement a classifier that predicts the probability of a compound being `active`. The compound dataset is grouped into `train`, and `test`. You should use `train` for training your classifier, and `test` for evaluation.

# Data

[cmpd.csv](Compound%20Classification%20db46bdb2256f447d8b527bbdfe3c6b82/cmpd.csv)

The data file consists of `InChIKey`, `SMILES`, `GROUP`, and `Activity` that looks like:

```
inchikey,smiles,group,activity
FNHKPVJBJVTLMP-UHFFFAOYSA-N,CNC(=O)c1cc(Oc2ccc(NC(=O)Nc3ccc(Cl)c(C(F)(F)F)c3)c(F)c2)ccn1,train,active
CUDVHEFYRIWYQD-UHFFFAOYSA-N,CNC(=O)c1cccc2cc(Oc3ccnc4cc(OCC5(N)CC5)c(OC)cc34)ccc12,train,active
TTZSNFLLYPYKIL-UHFFFAOYSA-N,Cc1cc2cc(Oc3ccnc(Nc4cccc(CS(=O)(=O)NCCN(C)C)c4)n3)ccc2[nH]1,test,active
UOVCGJXDGOGOCZ-UHFFFAOYSA-N,COc1cc2c(cc1F)C(c1ccccc1Cl)=Nc1c(n[nH]c1C)N2,train,active
CUIHSIWYWATEQL-UHFFFAOYSA-N,Cc1ccc(Nc2nccc(N(C)c3ccc4c(C)n(C)nc4c3)n2)cc1S(N)(=O)=O,test,active
IFPPYSWJNWHOLQ-UHFFFAOYSA-N,CCN(CC)CCOc1ccc(Nc2ncc3cc(-c4c(Cl)cccc4Cl)c(=O)n(C)c3n2)cc1,train,active
...
```

One may use other publicly open datasets, such as PubChem, ChEMBL, ChemSpider, and so on.

# Code and Notebook

The model should be written in `python`, and one should submit the code and/or `jupyter` notebook that implement a model with description.

One may use general purpose machine learning, deep learning libraries or modules, such as `sklearn`, `pandas`, `numpy`, `tensorflow`, and `torch`, some extensions of them, such as `torch-scatter`. `rdkit` is also allowed to use, but not beyond that, such as `dgl`,  `pyg`, and `deepchem`.

See the demo notebook below:

[cmpd_clf_demo.ipynb](Compound%20Classification%20db46bdb2256f447d8b527bbdfe3c6b82/cmpd_clf_demo.ipynb)

# Evaluation

Note that the model performance, coding structures and styles, and creative model/feature idea are comprehensively measured for the evaluation 

# Question and Submission

Feel free to ask questions to your first interviewer (cc to [recruit@bionsight.com](mailto:recruit@bionsight.com)) if you have any. Once you are done with the challenge, please send your code and jupyter notebook to your first interviewer and [recruit@bionsight.com](mailto:recruit@bionsight.com).