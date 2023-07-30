# 🪿 Han-solo
🪿 Han-solo: Thai syllable segmenter

This work wants to create a Thai syllable segmenter that can work in the Thai social media domain.

Dataset: [Han-solo: Thai syllable segmenter](https://zenodo.org/record/8196608)


## Dataset

This work uses 2 datasets:

1. Nutcha Dataset (Thai news domain). See more data_nutcha/
2. Han-solo: Thai syllable segmenter dataset (Thai social media domain). See more [Han-solo: Thai syllable segmenter](https://zenodo.org/record/8196608)

## Model

This work uses the CRE model that uses the same feature from [ssg](https://github.com/ponrawee/ssg) to the training model.

You can see the training notebook from train.ipynb.

The model file: han_solo.crfsuite

**F1-score**

1 is split, and 0 is not split.

```
              precision    recall  f1-score   support

           0       1.00      1.00      1.00     61078
           1       1.00      0.99      0.99     29468

    accuracy                           1.00     90546
   macro avg       1.00      1.00      1.00     90546
weighted avg       1.00      1.00      1.00     90546
```

## Cite as

> Wannaphong Phatthiyaphaibun. (2023). Han-solo: Thai syllable segmenter (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.8196608

or BibTeX entry:

``` bib
@dataset{wannaphong_phatthiyaphaibun_2023_8196608,
  author       = {Wannaphong Phatthiyaphaibun},
  title        = {Han-solo: Thai syllable segmenter},
  month        = jul,
  year         = 2023,
  publisher    = {Zenodo},
  version      = {1.0},
  doi          = {10.5281/zenodo.8196608},
  url          = {https://doi.org/10.5281/zenodo.8196608}
}
```