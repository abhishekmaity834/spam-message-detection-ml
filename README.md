# Spam Message Detection Using Machine Learning

## Project Overview
This project uses machine learning to classify text messages as spam or ham (not spam).

## Objectives
- Detect unwanted spam messages.
- Apply text preprocessing and feature extraction.
- Train a machine learning classification model.
- Evaluate the model's performance.

## Dataset
The project uses the SMS Spam Collection dataset.

- Original messages: 5,572
- Duplicate messages removed: 403
- Messages after cleaning: 5,169

## Technologies Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Methodology
1. Load and inspect the dataset.
2. Check missing values and remove duplicates.
3. Convert labels into numerical values.
4. Split the data into training and testing sets.
5. Extract text features using TF-IDF.
6. Train a Multinomial Naive Bayes classifier.
7. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
8. Test new messages using the trained model.

## Model Performance
- Accuracy: 96.62%
- Spam precision: 98.98%
- Spam recall: 74.05%
- Spam F1-score: 84.72%

## Conclusion
The model achieved 96.62% accuracy on the test dataset. It can classify new messages as spam or ham, although some spam messages may be missed.

## Future Improvements
- Test additional classification algorithms.
- Improve spam recall.
- Use an actual email dataset.
- Develop a web interface for message classification.
