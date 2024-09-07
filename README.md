# Word2Vec Model on Amazon Customer Reviews

## Overview
This project demonstrates the use of the Word2Vec library to build a word embedding model from customer reviews of phones and tablets purchased from Amazon. The objective is to train a model that captures semantic relationships between words based on the context in which they appear in the reviews. After training, the model is used to showcase word similarities and provide a list of similar words for given input words.

## Dataset
The dataset consists of Amazon customer reviews for phones and tablets. Each review describes the customer’s experience with the product, including aspects such as performance, usability, and design. The dataset is loaded and processed using `pandas` for use in the Word2Vec model.

## Project Structure
- **word2vec_model.py**: The script where the Word2Vec model is implemented and trained on the Amazon reviews dataset.
- **reviews_amazon.json**: The dataset containing customer reviews of phones and tablets purchased from Amazon.
- **README.md**: Project documentation (this file).

## Setup and Installation
    
1. **Install required libraries**:
    Make sure you have Python installed, and then install the necessary libraries using pip:
   
    pip install gensim pandas
    
    
3. **Download the dataset**:
   Ensure that the dataset file (reviews_amazon.json) is in the correct location.

## How It Works
1. **Load the Data**: The Amazon customer reviews dataset is loaded using pandas. Each review is preprocessed (e.g., tokenization, lowercasing) to prepare it for training the Word2Vec model.
  
2. **Train the Word2Vec Model**: The **gensim.models.Word2Vec** library is used to create and train a model on the customer review text data. The model learns word embeddings based on the context in which words appear in the reviews.

3. **Analyze Word Similarities**: After training the model, we use it to:
    - Find words similar to a given word based on their vector representations.
    - Measure the similarity between two words.

## Future Enhancements
- **Additional Preprocessing**: Implement more advanced preprocessing (e.g., removing stop words, handling contractions).

## Contributing
Feel free to contribute to this project by opening issues, submitting pull requests, or suggesting new features. Any contributions that improve the model or expand the dataset analysis are welcome!

## Contact
- **Umang Agarwal**
  - Email: agarwalumang830@gmail.com
  - LinkedIn: [Umang Agarwal](https://www.linkedin.com/in/umang-agarwal-985b081a1/)
  - GitHub: [@umangagarwal08](https://github.com/umangagarwal08)
