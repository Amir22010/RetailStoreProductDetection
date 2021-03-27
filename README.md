# Deep Learning Challenge - RetailStoreProductDetection

# Problem Overview
FMCG(Fast-Moving Consumer Goods) brands require insights into
retail shelves to help them improve their sales. One such insight comes
from determining how many products of their brands’ are present versus
how many products of competing brands are present on a retail store shelf.
This requires finding the total number of products present on every shelf in
a retail store.

# Problem Statement to Solve

- Given a grocery store shelf image, detect all products present in the
shelf image (detection only at product or no-product level)

- The assignment requires to implement a single shot object
detector with only “one” anchor box per feature-map cell.
- Accuracy of at least 0.7 mAP on the test set.

# Dataset Given

- The dataset to be used for training/testing is the Grocery dataset.
Link to the dataset: https://github.com/gulvarol/grocerydataset

- Please use the following link to download
ShelfImages.tar.gz(contains train and test splits) and replace
GroceryDataset_part1/ShelfImages with this.
https://storage.googleapis.com/open_source_datasets/ShelfImages.tar.gz


# Code Files Uploaded

- Training Colab Notebook - [Train](https://colab.research.google.com/drive/17rd4hmXe2-A2W6btvvDTMc83SDR5YMZ5?usp=sharing#scrollTo=SjNFUIVfYURL)

- Prediction Code Notebook - [Prediction](https://colab.research.google.com/drive/1MvyMbrrokyW4yTU__x3408kCm_bpvmIp?usp=sharing)


# Results

```javascript
{
'map@0.5' : 0.895
'map@0.75': 0.804
'averagePrecision@IOU_0.5': 0.895
'averagePrecision@IOU_0.75': 0.804
'averageRecall@IOU_0.5':0.70
}
```

# Test Images

![Result1](https://raw.githubusercontent.com/Amir22010/RetailStoreProductDetection/main/images/C1_P02_N2_S3_1.JPG)
![Result2](https://raw.githubusercontent.com/Amir22010/RetailStoreProductDetection/main/images/C1_P05_N2_S4_2.JPG)