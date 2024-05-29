# PPAD_torch
This repository contains a PyTorch implementation of PPAD.  
For more details, refer to the original paper https://academic.oup.com/bioinformatics/article/39/Supplement_1/i149/7210436， the original code is also provided in https://github.com/bozdaglab/PPAD.  

To run the implementation, execute the PPAD_torch.ipynb notebook. Note that the Masking layer in Keras has been replaced by two custom classes and the pack_padded_sequence function in PyTorch. The parameters of the model may require further tuning for optimal performance.
