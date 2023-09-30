# Torch_tabular_RNN
Using pytorch for tabular data; Implementation of custom torch datasets/dataloader; Comparison with LGBM

1. Import data & Simple data conversion
2. Implementation of custom dataset (__init__, __len__, __contains__, __getitem__) and torch dataloader with custom collate_fn
3. Implementation torch model with embedding and LSTM
4. 
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/721d6ce2-e80a-4c38-b54d-7d66b1fc94ef)

6. Training this model

![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/1768b31d-31a4-40e5-b285-f9b6b60cf995)

7. Evaluation of loss, metric, lr

![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/e3da64ae-5521-48c1-95ec-b97990c52bc5)
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/37440e4f-91d1-471b-b1e5-c0a7652a2e4c)
![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/b4940f3e-0541-4073-ba5f-52f5f02d9b33)


8. Scoring and calibration with torch logreg
9. Evaluation after calibration

![image](https://github.com/Monfin/Torch_tabular_RNN/assets/132058047/33b0b202-a72c-424c-ba82-e18e98e8db3c)

