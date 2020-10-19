# Deep-learning-based binary classifier (normal or abnormal) achieves a PERFECT classification on 108,308 two-dimensional retinal OCT images

This repository includes source code of deep-learning-based binary classifier (normal or abnormal) for classification on two-dimensional retinal OCT images. 
<br>
The detail of the model is described in our paper (Deep learning achieves perfect anomaly detection on 108,308 retinal images including unlearned diseases, https://arxiv.org/abs/2001.05859). The code shown here corresponds to Supplementary Fig. 1 in our paper.

# Requirement
 
* Python 3.6.9
* Keras 2.2.5
* tensorflow 1.13.1
* tensorflow-gpu 1.13.1
* scikit-learn 0.21.2
<br>
To run the model, jupyter notebook can be used. We recommend you to use the ipynb files of this repository for running the model. Please upload ipynb files of this repository to Google Colaboratory or etc.

# Usage
 
1. Datasets used for training and testing the model is available from the following URL:<br>
Dataset α: https://data.mendeley.com/datasets/rscbjbr9sj/3<br>
Dataset β: https://sites.google.com/site/hosseinrabbanikhorasgani/datasets-1

2. Use "Resize.ipynb" to resize the images to 299x299x3.<br>
3. Use "Train.ipynb" to train the model.<br>
4. Use "Test.ipynb" to test the model.<br>
 
# Note
 
Please note that we cannot answer any technical issues.
 
# Author
 
Ayaka Suzuki & Yoshiro Suzuki
 
# License
Our code is under [GNU Affero General Public License v3.0](https://choosealicense.com/licenses/agpl-3.0/).
 
