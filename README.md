# Assignment 2 Text Classification

## Introduction
This file provides the implementation for a text classifier designed to identify emotions in textual data. The project utilizes various NLP techniques and machine learning models to preprocess the data, extract features, and classify emotions effectively. It includes functionality for data cleaning, feature engineering, model training, evaluation, and visualization of results.

---

## Python Version and Dependencies

### Python Version
- The code was developed and tested using **Python 3.10**.

### Third-Party Libraries and Versions
The following libraries are required to run the code:
- **pandas**: 1.5.3
- **matplotlib**: 3.6.3
- **seaborn**: 0.11.2
- **nltk**: 3.9.1
- **scikit-learn**: 1.1.3
- **wordcloud**: 1.9.2

---

## How to Run the Code

1. **Install Python**  
   Ensure you have Python 3.10 or a compatible version installed. You can download it from the [official Python website](https://www.python.org/).

2. **Install and Open the Text Classifier Program**  
   If Jupyter Notebook is not already installed, install it using the following command:
   ```bash
    pip install notebook
   ```
   Once installed, open the Jupyter Notebook environment by running:
      ```bash
    jupyter notebook
   ```

3. **Install Dependencies**  
  To ensure the program works correctly, install the required Python libraries. Uncomment the following `!pip` commands in the first cell of the notebook and run them:
   ```bash
   !pip install pandas matplotlib seaborn nltk scikit-learn wordcloud
   ```

4. **Download NLTK Data**  
   If you encouter a **missing resource error** for using ntlk uncomment the follwing command (in the import statements cell) and run it:
   ```bash
    import nltk
    nltk.download('stopwords')  # For stop words
    nltk.download('wordnet')    # For lemmatization
    nltk.download('punkt')      # For tokenization
   ```

5. **Run the Notebook**  
  Run the cells sequentially

6. **Troubleshooting**  
   If you encounter missing module errors, double-check that all dependencies are installed.
    Ensure your Python environment matches the dependencies in the notebook

---

## Notes
- Ensure that your environment is correctly configured with the necessary versions of the libraries.
- For troubleshooting library versions, use the `pip show` command to verify installations.

---

If you need further assistance, please reach out!
