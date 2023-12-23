# <img src="https://github.com/sshaghayeghs/LLaMA-VS-ChatGPT/blob/main/Image/SMILINGLLaMA.png" width="60" height="60"> Comparative Analysis of `LLaMA` and `ChatGPT` Embeddings for `SMILES` Strings 


**`Purpose:`** `Large Language Models (LLMs)` like `ChatGPT` and `LLaMA` are
increasingly recognized for their potential in the field of cheminformatics,
particularly in interpreting Simplified Molecular Input Line Entry System
`(SMILES)`, a standard method for representing chemical structures. These
LLMs can decode SMILES strings into vector representations, providing a novel
approach to understanding chemical graphs.

**`Methods:`** We investigate the performance of ChatGPT and LLaMA in
embedding SMILES strings. Our evaluation focuses on two key applications:
`molecular property (MP)` prediction and `drug-drug interaction (DDI)` prediction,
both essential in drug development and healthcare.
Results: We find that SMILES embeddings generated using LLaMA outperform
those from ChatGPT in MP and DDI prediction tasks. Notably, LLaMA-based
SMILES embeddings demonstrate accuracy comparable to existing methods in
both areas.

**`Conclusion:`** The application of LLMs in cheminformatics, particularly in
utilizing SMILES embeddings, shows significant promise for advancing drug
development. This includes improving the prediction of chemical properties and
facilitating the drug discovery process.


# Gold Standard Datasets
  **`DDI Network`** [BioSnap](https://github.com/sshaghayeghs/DDI-LLM/blob/main/Dataset/DDI/BioSNAP_ChCh-Miner_ChCh-Miner_durgbank-chem-chem.tsv) & [DrugBank](https://github.com/sshaghayeghs/DDI-LLM/blob/main/Dataset/DDI/DrugbankDDI.csv)

  **`MoleculeNet`** [BBBP](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/BBBP.csv), [BACE C](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/bace.csv), [HIV](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/HIV.csv), [ClinToX](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/clintox.csv.gz) (These datasets can be obtained from [DeepChem](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html))

