# Spam Email Detection using Machine Learning

## Description

This project is a Machine Learning-based system that classifies messages into two categories: **Spam** and **Not Spam (Ham)**. It uses text processing techniques and a Naive Bayes classifier to automatically detect unwanted messages.

---

## Features

* Text preprocessing (cleaning and normalization)
* TF-IDF vectorization for feature extraction
* Multinomial Naive Bayes classification
* High accuracy on test data

---

## Technologies Used

* Python
* Pandas
* Scikit-learn

---

## Dataset

The project uses the **SMS Spam Collection Dataset**, which contains labeled messages as spam or ham.

---

## How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
cd Spam-Detection-Project
```

2. Install required libraries:

```bash
pip install pandas scikit-learn
```

3. Run the project:

```bash
python main.py
```

---

## Example

**Input:**

```
Congratulations! You have won a free lottery ticket
```

**Output:**

```
Spam
```

---

## Project Structure

```
Spam-Detection-Project/
│
├── main.py        # Main Python script
├── spam.csv       # Dataset file
├── README.md      # Project documentation
└── report.pdf     # Project report
```

---

## Future Improvements

* Implement Deep Learning models (LSTM, BERT)
* Deploy as a web application
* Improve accuracy with larger datasets

---

## Author

Hardik Saini
Registration Number: 25BCE10544

