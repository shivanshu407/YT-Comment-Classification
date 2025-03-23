# YouTube Comment Classification

## Overview
This project focuses on classifying YouTube comments into different categories using machine learning techniques. The model was trained using natural language processing (NLP) techniques to analyze and categorize comments efficiently.

## Features
- Preprocessing of YouTube comments
- Feature extraction using NLP techniques
- Machine learning model for classification
- Performance evaluation and visualization

## Dataset
The dataset consists of YouTube comments labeled according to predefined categories. Data preprocessing involved:
- Tokenization
- Stopword removal
- Lemmatization
- TF-IDF vectorization

## Technologies Used
- **Programming Language**: Python
- **Libraries and Frameworks**:
  - Scikit-Learn
  - NLTK
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

## Model Training
The model was trained using various machine learning algorithms, including:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Naïve Bayes

## Results
The best-performing model was evaluated based on accuracy, precision, recall, and F1-score. The detailed results are documented in the `Results.pdf` file included in this repository.

## Installation
To run the project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivanshuMishra/YouTube-Comment-Classification.git
   cd YouTube-Comment-Classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to preprocess data and train the model:
   ```bash
   jupyter notebook YT_Comment_Classification.ipynb
   ```

## Usage
- Modify the dataset or preprocessing steps as needed.
- Train and test different models for performance comparison.
- Use the trained model to classify new YouTube comments.

## Author
This project was developed by **Shivanshu Mishra**.

## License
This project is open-source and available under the MIT License.

