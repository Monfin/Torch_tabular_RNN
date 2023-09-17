# Torch_tabular_RNN
Using pytorch for tabular data; Implementation of custom torch datasets/dataloader; Comparison with LGBM

### Import data & Simple data conversion
### Implementation of custom dataset (__init__, __len__, __contains__, __getitem__) and torch dataloader with custom collate_fn
### Implementation torch model with embedding for categorical features and a dense network for numerical features:
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/e4ab9ac6-0bbc-4165-923f-4c67ebdf642d)
### Training this model:
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/bf06d82c-c3ff-4798-b15f-f31241742cac)
### Scoring and calibration with torch logreg
### Evaluation after calibration:
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/2c8a856c-858d-4ed6-9884-c931173cc622)
### Comparison with LGBM via torch:
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/08f9d939-6eba-4213-878f-5c307bfd7437)
