
# Spam Email Detection App using Machine Learning

A machine learning-based web application that detects whether an email message is **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

## Overview

Spam emails are one of the most common cybersecurity threats, often used for phishing, scams, and malware distribution. This project applies machine learning algorithms to classify email content and improve email security.

The application analyzes the text of an email and predicts whether it is spam based on a trained classification model.

## Features

* Spam vs Ham email classification
* Machine Learning prediction system
* Text preprocessing using NLP
* Real-time message analysis
* User-friendly web interface
* Fast and lightweight deployment

## Technologies Used

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* Natural Language Processing (NLP)
* HTML/CSS
* Pickle

## Machine Learning Workflow

1. Data Collection
2. Text Cleaning and Preprocessing
3. Tokenization
4. Stopword Removal
5. TF-IDF Vectorization
6. Model Training
7. Prediction and Classification

## Dataset

The model was trained using a spam email dataset containing labeled spam and ham messages.

Example labels:

* Spam
* Ham

## Model Used

Example algorithms commonly used:

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

## Installation

Clone the repository:

```bash
git clone https://github.com/youness7777777/spam-detector.git
```

Navigate to the project folder:

```bash
cd spam-detector
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

## Usage

1. Open the application in your browser
2. Enter an email message
3. Click on the Predict button
4. The system will classify the message as:

   * Spam
   * Not Spam

## Example

Input:

```text
Congratulations! You won a free iPhone. Click here now!
```

Output:

```text
Spam
```

## Project Structure

```text
spam-detector/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── templates/
├── static/
└── README.md
```

## Future Improvements

* Deep Learning integration using LSTM/BERT
* Email attachment scanning
* Phishing URL detection
* API deployment
* Docker support
* Multi-language spam detection

## Applications

* Email filtering systems
* Cybersecurity solutions
* Anti-phishing tools
* Enterprise email protection

## License

This project is open-source and available under the MIT License.

## Author

Developed by Youness


<img width="1280" height="681" alt="image" src="https://github.com/user-attachments/assets/ac1ca5e9-851b-400e-9429-cabac5ebaba3" />
<img width="1280" height="670" alt="image" src="https://github.com/user-attachments/assets/affb56ca-1a32-46cb-b187-0af515b31697" />
