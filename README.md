# Text Classification using CNN

This project focuses on classifying emails into one of 20 different categories, utilizing a Convolutional Neural Networks (CNN) for text classification. The dataset consists of text files representing emails, with labels corresponding to each text file embedded in the file name.

## Project Overview
**Data Preparation:** The Python os library is used to access and extract all text files into a Pandas DataFrame. File names are then processed to extract the corresponding labels for each email.

**Text Preprocessing:** The re (regular expression) library is employed for various text preprocessing tasks, including extraction of email addresses and subjects, removal of unnecessary words and special characters, and named entity recognition.

**Text Vectorization:** Global Vectors (GloVe) are applied to the preprocessed text to obtain a numerical representation suitable for the deep learning model.

**Model Design and Evaluation:** Two different 1D-CNN architectures are implemented and compared based on their F1-scores, with the best model achieving an F1-score of 83.5%.

## Results
The project effectively showcases the application of 1D-CNNs for multi-class email classification. The best model achieves a noteworthy F1-score of 83.5%. This result highlights the potential of using deep learning techniques to accurately classify text data across various categories.
