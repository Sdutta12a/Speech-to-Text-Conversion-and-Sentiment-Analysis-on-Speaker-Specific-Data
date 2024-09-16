# Speech-to-Text-Conversion-and-Sentiment-Analysis-on-Speaker-Specific-Data
In this project, development of a pipeline for emotion detection from speech data, starting with speechto-text conversion using the Google Speech Recognition API, followed by sentiment and emotion
classification is being done. A pre-trained DistilRoBERTa model from Hugging Face was used to
classify emotions like joy, sadness, and anger from the transcribed text.
The model’s performance is being evaluated using accuracy, precision, recall, and F1-score, achieving
79% accuracy on a dataset of 40 data points. Performance varied across emotion classes due to dataset
size and class imbalance. Future improvements will focus on expanding the dataset and balancing
emotion categories to enhance model generalization.
