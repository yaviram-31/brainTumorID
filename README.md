# brainTumorID
Primitive algorithm for identifying meningiomas in an MRI scan of a brain. 

The program utilizes the MATLAB Image Processing Toolkbox to:

1. emphasize any large and solid shapes (if there are any)
2. binarize the image
3. take the row sum, and if any point is a very prominent maximum it is identified as a meningioma
4. if a tumor is identified, the boolean isTumor will be True. Otherwise it is False.

MRI scan dataset was found at:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
