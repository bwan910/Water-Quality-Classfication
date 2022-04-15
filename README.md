# Water-Quality-Classfication: Project Overview
**This project serves as an educational purpose. It is for assignment purposes. Do not use for real life scenarios.**
<p>The idea of this project is a binary classfication for determining whether the water quality is good or bad based on the given water ingredient attributes.</p>

## Folders & Files Structure:
1) Folder Water_quality_prediction_models: Consist dataset files and all model training files.
2) Folder Streamlit_water_quality_prediction: Consist Streamlit application source code file and trained model in h5 format file. 


## Methodology
- Obtained Data from Kaggle: https://www.kaggle.com/datasets/mssmartypants/water-quality
- Exploratory Data Analysis were performed to explore dataset.
- Data Preprocessing.
- Splitting of Data. Ratio 80% Training and 20% Testing. 
- Optimized few Machine Learning and Deep Learning algorithms to obtain the best model: 
  1) Decision Tree 
  2) K-Nearest Neighbors
  3) Gaussian Naive Bayes
  4) Artificial Neural Network
 
- Model evaluated with a few different metrics (Accuracy, Precision, Recall and etc)
- Built a web interface using Streamlit for testing the model.

## Model Findings
### Accuracy:
| Model                     | Accuracy Score    | 
| -------------             | -------------     |
| Gaussian Naive Bayes      | 85%               |
| Decision Tree             | 92.6%             |
| K-Nearest Neighbour       | 93.1%             |
| Artificial Neural Network | 93.8%             |
