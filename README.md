# XX_NER_WordCamouflage Dataset

## Information

The dataset available in this repository is a synthetic multilingual dataset that has been designed to detect word camouflage techniques in over 20 languages. The dataset has been created by using text data from various sources, including OPUS News-Commentary, OPUS ParaCrawl, TED2020, and WikiMatrix.

The dataset has been created by first generating non-camouflaged text data from multiple sources. After this, camouflage techniques like leetspeak, punctuation insertion, and syllable inversion have been applied to the text data using the [pyleetspeak](https://pypi.org/project/pyleetspeak/) package. The data has been annotated and tagged to represent different camouflage methods, and parameters applied to each instance are documented for interpretability. The final dataset is divided into three sets - training, validation, and testing sets. It is important to note that the camouflage has been exclusively generated using the generator tool.

This dataset can be used to train models to recognize camouflaged entities in both monolingual and multilingual contexts. The dataset's unique aspect is that it focuses on word camouflage techniques, making it a valuable resource for research on content moderation evasion. The dataset is part of a larger effort to combat information disorders on social networks, and it's publicly available for research and application, promoting transparency and reproducibility in the field. The dataset is a part of a paper [publication](https://doi.org/10.1016/j.asoc.2023.110552).

## Cite

If you use the dataset please cite these contributions:

```
@article{HUERTASGARCIA2023110552,
title = {Countering malicious content moderation evasion in online social networks: Simulation and detection of word camouflage},
journal = {Applied Soft Computing},
volume = {145},
pages = {110552},
year = {2023},
issn = {1568-4946},
doi = {https://doi.org/10.1016/j.asoc.2023.110552},
author = {Álvaro Huertas-García and Alejandro Martín and Javier Huertas-Tato and David Camacho},
}
```

```
@inproceedings{NLP_MisInfo2023,
  author       = {{\'{A}}lvaro Huertas{-}Garc{\'{\i}}a and
                  Alejandro Mart{\'{\i}}n and
                  Javier Huertas{-}Tato and
                  David Camacho},
  title        = {Countering Malicious Content Moderation Evasion in Online Social Networks:
                  Simulation and Detection of Word CamouflageS},
  booktitle    = {Proceedings of the NLP-MisInfo Workshop co-located
                  with 39th International Conference of SEPLN},
  series       = {{CEUR} Workshop Proceedings},
  volume       = {3525},
  pages        = {10--14},
  publisher    = {CEUR-WS.org},
  year         = {2023},
  url          = {https://ceur-ws.org/Vol-3525/paper1.pdf},
}
```
