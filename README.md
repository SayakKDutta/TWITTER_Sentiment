# Twitter Sentiment Analysis LSTM

## Project Summary
This Twitter Sentiment Analysis LSTM project aims to classify tweets into positive or negative sentiments using LSTM (Long Short-Term Memory) neural networks. 
The dataset used contains tweets labeled with sentiments, and the goal is to build a model that accurately predicts the sentiment of a given tweet.

## About Dataset
### Motivation
Hate speech is an unfortunately common occurrence on the Internet. Often social media sites like Facebook and Twitter face the problem of identifying and censoring problematic posts while weighing the right to freedom of speech. 
The importance of detecting and moderating hate speech is evident from the strong connection between hate speech and actual hate crimes. Early identification of users promoting hate speech could enable outreach programs that attempt
to prevent an escalation from speech to action. Sites such as Twitter and Facebook have been seeking to actively combat hate speech. 
In spite of these reasons, NLP research on hate speech has been very limited, primarily due to the lack of a general definition of hate speech, an analysis of its demographic influences, and an investigation of the most effective features.


## Dataset Overview
- The dataset contains tweets with sentiments labeled as positive(0) or negative(1).
- Preprocessing steps include tokenization, lemmatization, and converting words to word vectors using pre-trained GloVe embeddings.
- Exploratory data analysis is limited due to the nature of the task, focusing more on model evaluation metrics.

## Project Goal 
The goal of this project is to develop a sentiment analysis model that can classify tweets into positive or negative categories based on their content. The model's performance is evaluated based on metrics such as accuracy, precision, recall, and F1-score.


## Modeling Approach
- Tokenization and lemmatization are performed using NLTK (Natural Language Toolkit).
- Word vectors are generated using pre-trained GloVe embeddings to represent words numerically.
- LSTM (Long Short-Term Memory) neural networks are implemented for sentiment classification.
- The model is compiled with binary cross-entropy loss and optimized using the Adam optimizer.
- Class weights are used to handle class imbalance, giving more weight to the minority class (positive sentiments).
- Model training is monitored using validation data and checkpoints to save the best-performing model.

## Conclusion
- LSTM neural networks show promising results in classifying tweet sentiments.
- Class imbalance is addressed using class weights to improve model performance.
- Evaluation metrics such as accuracy, precision, recall, and F1-score provide insights into model performance.

## Acknowledgments
The dataset used in this analysis is publicly available and can be found at [Twitter Sentiment Analysis - Analytics Vidya](https://www.kaggle.com/datasets/dv1453/twitter-sentiment-analysis-analytics-vidya?select=train_E6oV3lV.csv).

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact
For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com].
