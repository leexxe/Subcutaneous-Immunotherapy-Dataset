# Dataset for Patient Adherence in Subcutaneous Immunotherapy for Allergic Rhinitis

## Overview
This dataset encompasses data from 205 patients undergoing subcutaneous immunotherapy for allergic rhinitis. The dataset includes various demographic and clinical attributes of patients, reasons for therapy cessation, and score measurements over time.

## Utilization Guidelines

This dataset contains detailed information crucial for predicting patient adherence in subcutaneous immunotherapy for allergic rhinitis. It includes:

- **Columns 1:** These columns capture the reasons for therapy cessation and the corresponding time. 
- **Columns 2-18:** Basic patient information, encompassing various demographic and clinical attributes.
- **Columns 19 onwards:** These columns are dedicated to score measurements recorded at different time intervals - 0, 4, 12, 18, 24, and 36 months, providing a longitudinal view of patient outcomes. 

The dataset was randomly partitioned into training/validation and testing subsets. To replicate the exact dataset division as presented in our study, you may employ one of the following methods:

1. **Using sklearn.model_selection**:
   Employ the `train_test_split` function, setting `test_size=0.2` and `random_state=42`.

2. **Using Predefined Indices**:
   Access the indices directly in the `data` folder.

## License

This project is licensed under the Creative Commons Attribution (CC BY) 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details.

## Citing Our Work
If you use this dataset for your research, please cite our [paper](https://arxiv.org/pdf/2401.11447.pdf):

```bibtex
@article{Li2024Sequential,
  title={Sequential Model for Predicting Patient Adherence in Subcutaneous Immunotherapy for Allergic Rhinitis},
  author={Li, Yin and Xiong, Yu and Fan, Wenxin and Wang, Kai and Yu, Qingqing and Si, Liping and van der Smagt, Patrick and Tang, Jun and Chen, Nutan},
  eprint={2401.11447},
  archivePrefix={arXiv},
  year={2024},
}
```