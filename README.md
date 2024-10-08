# Species Classification Based on Web Scraped Images with Explainable AI (XAI)
## Overview
This project focuses on classifying species using images scraped from the web, leveraging various deep learning models to analyze the data. The objective is to create an accurate and interpretable classification system, allowing users to understand the model's decisions through Explainable AI (XAI) techniques.

## Models Used
The following machine learning models were implemented in the classification task:

* Support Vector Machine (SVM): 46.67%
* Convolutional Neural Network (CNN): 55.83%
* MobileNetV3Large: 42.53%
* DenseNet: 95.68%
* Inception: 92.36%
* Xception: 98.61%

Among these, the Xception model achieved the highest accuracy, demonstrating its effectiveness for species classification based on visual data.

## Data Preparation:

i. Place your web scraped images in the data/images/ directory.
Ensure your labels or annotations are correctly formatted in the data/annotations/ folder.
Training Models:

ii. Open the Jupyter notebooks in the notebooks/ directory to train and evaluate the models.
Each notebook provides detailed steps for training and assessing performance.
Explaining Predictions:

iii. Utilize XAI techniques integrated into the notebooks to visualize and understand model predictions.

## Conclusion
This project successfully demonstrates the application of deep learning for species classification using web-sourced images. The integration of Explainable AI techniques enhances the interpretability of model predictions, making this tool valuable for researchers and conservationists alike.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments
Thank you to Arun Kumawat and all contributors and libraries that made this project possible, including TensorFlow, Keras, and Scikit-learn.
