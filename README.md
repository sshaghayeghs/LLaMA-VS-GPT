# <img src="https://github.com/sshaghayeghs/LLaMA-VS-ChatGPT/blob/main/Image/SMILINGLLaMA.png" width="60" height="60"> Large Language Models in `Molecular Embeddings`
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11faD4z6Au0i9RkyRZeY4QqIFR85fqUfo?usp=sharing)

**`Purpose:`** Large Language Models (LLMs) like `GPT (Generative Pre-trained Transformer)` from `OpenAI` and `LLaMA (Large Language Model Meta AI)` from `Meta AI` are increasingly recognized for their potential in the field of cheminformatics, particularly in understanding Simplified Molecular Input Line Entry System `(SMILES)`, a standard method for representing chemical structures. These LLMs also have the ability to decode SMILES strings into vector representations.

**`Method:`** We investigate the performance of GPT and LLaMA compared to pre-trained models on SMILES in embedding SMILES strings on downstream tasks, focusing on two key applications: molecular property prediction and drug-drug interaction prediction.

**`Results:`** We find that SMILES embeddings generated using LLaMA outperform those from GPT in both molecular property and DDI prediction tasks. Notably, LLaMA-based SMILES embeddings show results comparable to pre-trained models on SMILES in molecular prediction tasks and outperform the pre-trained models for the DDI prediction tasks.

**`Conclusion:`** The performance of LLMs in generating SMILES embeddings shows great potential for further investigation of these models for molecular embedding. We hope our study bridges the gap between LLMs and molecular embedding, motivating additional research into the potential of LLMs in the molecular representation field.


# Gold Standard Datasets
  **`DDI Network`** [BioSnap](https://github.com/sshaghayeghs/DDI-LLM/blob/main/Dataset/DDI/BioSNAP_ChCh-Miner_ChCh-Miner_durgbank-chem-chem.tsv) & [DrugBank](https://github.com/sshaghayeghs/DDI-LLM/blob/main/Dataset/DDI/DrugbankDDI.csv)

  **`MoleculeNet`**   datasets can be obtained from [DeepChem](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html)

