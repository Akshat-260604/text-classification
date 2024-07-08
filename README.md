I created a text classification model to analyze sentiments in the IMDB 50k movie review dataset, leveraging machine learning (ML) and natural language processing (NLP) techniques. The process began with data preprocessing, which involved cleaning the text data by removing HTML tags, punctuation, and stop words, and then converting the text to lowercase. Tokenization and lemmatization were employed to transform the text into a format suitable for analysis.

Using the Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) methods, I converted the textual data into numerical vectors. These vectors served as inputs to the ML models. I experimented with various algorithms, including Logistic Regression, Naive Bayes, and Support Vector Machines (SVM), optimizing hyperparameters to enhance model performance.

The model training involved splitting the dataset into training and testing sets, ensuring robust evaluation. Accuracy, precision, recall, and F1-score metrics were used to assess the model's effectiveness. Among the tested models, SVM demonstrated the highest accuracy in classifying movie reviews as positive or negative.

It's important to note that this project is not end-to-end and is not deployed yet. The current scope includes model development and evaluation, with deployment planned for future phases.
