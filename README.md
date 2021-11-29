# Architectures for Multi-target Image Classification

This dataset contains splendid photographs of architecures as jpg images.

`architecture_annotated.csv` is the annotation file where images are classified into following three targets:
1. `file_name`: str[unique values] - represents jpg image file name
2. `trees`: str['present', 'not present'] - `present` represents presence of trees and `not present` represents otherwise.
3. `lights_on`: str['yes', 'no'] - `yes` represents presence of turned-on-lights and `no` represents otherwise.
4. `people`: str['present', 'not present'] - `present` represents presence of people and `not present` represents otherwise.

Annotations are performed manually.

`architecture_labels.jpg` exposes the class distribution of features.
![img](https://raw.githubusercontent.com/RajkumarGalaxy/Architectures/main/architecture_labels.jpg)
