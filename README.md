# Danish_NER

## Data Source

[CoNLL 2003 Dataset](https://www.aclweb.org/anthology/W03-0419.pdf)

## Description

- Built named entity reconizer to achieve cross-lingual transfer learning from English source data to Danish target data
- Utilized SpaCy Model and embeddings for training
- Performed result analysis by looking into name formes in both languages

## Results

| Model | F-score (Dev set) |
|-------|---------|
| Danish NER | 0.5419 |
| Danish NER + Bi-lingual embedding | 0.5748 |
| English NER + Fine-tuning on Danish | 0.6289 |

## Credits

This task is designed and mentored by my instructor [Miikka Silfverberg](https://mpsilfve.github.io/) from my Low-Resources Languages class in UBC.
