# Breast Cancer Classification using deep learning model developed by ablation study on pre-processed mammography images

In this study, we will be showcasing a computer vision classification problem using mammograms. The dataset we have used can be downloaded from https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM. It consists of four classes:

Benign Calcification
Benign Mass
Malignant Calcification
Malignant Mass

Therefore, this is a multi-class classification problem. The images containes artifacts and noises which may cause reducing model's performance. Hence, artifacts and noises are removed and images are enhanced by adjusting overall brightness and contrast. After pre-processing the images, the dataset is augmented as the number of images were not sufficient for a deep learning model. Finally, the model is developed using ablation study by altering several components and hyper parameters of CNN architecture.
