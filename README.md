📂 **SMS Spam Detection using SVM**

This project applies Support Vector Machine (SVM) for classifying SMS messages as Spam or Ham (Not Spam) using the SMS Spam Collection Dataset.

📊 **Dataset**
- Name: SMS Spam Collection
- Source: UCI Machine Learning Repository
- Format: Tab-separated file with two columns:
- label: Spam or Ham
- message: SMS text content

🔍 **Project Workflow**
- Data Loading
- Loaded the SMS Spam Collection dataset (tab-separated format).
- Preprocessing
- Converted labels to binary (ham = 0, spam = 1).
- Applied text cleaning:
- Lowercasing
- Removing punctuation and numbers
- Stopword removal
- Lemmatization
- Feature Extraction
- Used TfidfVectorizer to convert cleaned messages into numerical feature vectors.
- Model Training
- Applied Support Vector Machine (SVM) with a linear kernel.
- Evaluation
- Achieved an accuracy of 98.20% on the test set.
- Evaluated using accuracy, precision, recall, and F1-score.

📈 **Results**
Model: SVM (Linear Kernel)

Accuracy: 98.20%

Performance: The model efficiently distinguishes spam from ham messages with high accuracy.

🛠️ **Technologies Used**
- Python
- Pandas
- Scikit-learn
- NLTK (for text preprocessing)

