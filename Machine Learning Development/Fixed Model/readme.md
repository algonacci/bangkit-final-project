# Skin Cancer Detection:

  Source Datasets: <br>
  https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000
  <br>
 
  This datasets contains of 10000 picture of Skin disease with 7 Classes:

  | Name | Kind of Cancer |
  |------------|------|
  | Actinic keratoses | Benign |
  | Basal cell carcinoma | Benign |
  | Benign keratosis-like lesions| Benign |
  | Dermatofibroma | Benign |
  | Melanocytic nevi | Benign |
  | Melanoma | Malignant | 
  | Vascular lesion | Benign |

  <br>
 
  with Melanoma is Malignant (Deadliest Cancer) and else is Benign (Not Deadliest Cancer)

  but we divided it into only 2 Classes, Melanoma classify as Malignant and Actinic Keratoses, Basal Cell Carcinoma, Benign keratosis-like lesion, Dermatofibroma, Melanocytic Nevi and Vascular lession as Benign. here is the modified datasets: <br> https://drive.google.com/file/d/1-dOK_6g-Bkf8_SKcZKUwiCIj8TSqC7O5/view?usp=sharing <br>

  so the label will be:<br>

  | Name | Kind of Cancer | Label |
  |------------|------|------|
  | Actinic keratoses | Benign | 0 |
  | Basal cell carcinoma | Benign | 0 |
  | Benign keratosis-like lesions| Benign | 0 |
  | Dermatofibroma | Benign | 0 |
  | Melanocytic nevi | Benign | 0 |
  | Melanoma | Malignant | 1 |
  | Vascular lesion | Benign | 0|

  <br>
  
  Here we using Machine Learning with Tensorflow as framework to Classify the skin disease, here is the Saved Model (*.h5 format) with 98.02% Accuracy Score and 91.2% Val_Accuracy Score with using Xception transfer learning, Adam optimizer, and sigmoid activation function): <br> https://drive.google.com/file/d/1-0ODyEWBJcERmvXXM5Ejk_VoxV7gI6SW/view?usp=sharing
