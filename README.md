# Face Mask Detection using CNN

##1.Project Overview
This project is a real-time face mask detection system using Convolutional Neural Networks (CNN).  
It classifies faces in images or video stream as **Mask** or **No Mask**, useful for safety monitoring.

##2.Dataset
- Public face mask dataset (masked and unmasked face images) downloaded from Kaggle.  
- Train–test split: 80% training, 20% testing.  
- Applied image augmentation (rotation, zoom, flip) to improve generalization.

##3.Tech Stack
- Language: Python  
- Libraries: TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib, Seaborn  
- Tools: Jupyter Notebook / Google Colab, GitHub for version control.
##4.Training & Metrics
- Model: Custom CNN architecture for binary classification.  
- Metrics: Accuracy, Precision, Recall, F1-score.  
- Final test accuracy: **(இங்க உங்க actual accuracy value type பண்ணுங்க, example: 95%)**.

##5.How to Run
1. Clone this repository  
git clone https://github.com/aadhimithran/Face-mask-detection-deep-learning-.git
cd Face-mask-detection-deep-learning-
2. Install dependencies  
pip install -r requirements.txt
3. Run the notebook or script  
jupyter notebook
