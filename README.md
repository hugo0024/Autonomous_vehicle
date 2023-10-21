# Autonomous Driving Car Using Deep Learning
This repository contains the research project on autonomous driving cars using deep learning. The project explores the possibilities of using various machine learning models, including self-trained and pre-trained models, to simulate self-driving capabilities on the Picar-V from SunFounder.

# Methodology
1. Data Preprocessing: The dataset, consisting of 13,798 images along with the corresponding target car response (speed and steering angle), is inspected and corrupted image files are removed. The steering angles and speeds are normalized between 0 and 1.
2. Image Data Augmentation: To reduce overfitting and improve model performance, image data augmentation techniques such as zooming, panning, brightness adjustment, blurring, and flipping are applied randomly to the training data.
3. Model Development: A total of 6 different Convolutional Neural Network (CNN) models are developed and tested. This includes 3 custom models trained from scratch and 3 models utilizing pre-trained networks. The models are trained on 80% of the dataset and validated on the remaining 20%. Early stopping regularization is implemented to stop training when there is no improvement on the validation loss.
4. Model Evaluation: The performance of the models is assessed based on their ability to predict the appropriate speed and steering angle from an image. Metrics such as accuracy, mean squared error, and mean absolute error are used to evaluate the models.

The research project yields the following results:

1. Model Performance: The performance of the developed CNN models is evaluated and compared. The models demonstrate varying levels of accuracy and predictive capabilities in predicting speed and steering angle.
2. Comparison with Existing Models: The project compares the performance of the developed models with existing models such as Nvidia's End-to-End Deep Learning for Self-Driving Cars project. Insights are gained into the effectiveness of different CNN architectures for self-driving tasks.
3. Recommendations for Improvement: The project explores the potential for further improving the performance of self-driving models by experimenting with different CNN architectures and techniques.
