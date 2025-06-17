# Custom-Dataset-for-VLMEvalKit
Some Custom Datasets for VLMEvalKit

# ViLP dataset
The dataset comes from the paper "Probing Visual Language Priors in VLMs"

Simply add the following to the DATASET_URL of ImageVQADataset at file "vlmeval/dataset/image_vqa.py"
```
'ViLP': 'ViLP.tsv',
```
