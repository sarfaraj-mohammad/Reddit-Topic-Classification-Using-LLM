# Reddit Topic Classification Using LLM

This repository contains the code and resources for fine-tuning a BERT model to classify Reddit posts into distinct categories based on opposing viewpoints. The dataset was created by scraping posts from two subreddits with contrasting perspectives, resulting in a balanced dataset with over 100 examples per category.

## Project Overview

The primary objective of this project was to fine-tune a pre-trained BERT model for the task of topic classification. The dataset comprises Reddit posts from two opposing subreddits, allowing for the exploration of how well a model can distinguish between these viewpoints.

### Steps:
1. **Dataset Creation:** 
   - Scraped posts from subreddits with opposing viewpoints.
   - Preprocessed the text to remove noise, ensuring clean input data for training.
   - The dataset includes over 200 examples, with balanced representation from both categories.

2. **Data Splitting:**
   - Split the dataset into training (160 examples) and test (40 examples) sets.
  
3. **Model Fine-Tuning:**
   - Used the Hugging Face Transformers library to fine-tune a BERT model on the training data.
   - Evaluated the model on the test set to determine its accuracy in classifying new posts.

4. **Results:**
   - Reported the test accuracy of the fine-tuned model.
   - Discussed potential improvements for model accuracy, including data augmentation, hyperparameter tuning, and experimenting with different model architectures.

### How to Use
- **Data:** The dataset used for training and testing is included in this repository.
- **Code:** The fine-tuning code is written in Python using the Hugging Face Transformers library.
- **Tutorial:** Follow the steps outlined in the Jupyter notebooks to replicate the results or adapt the model for your own text classification tasks.

### Future Work
- Explore alternative language models (e.g., GPT, RoBERTa) for improved accuracy.
- Expand the dataset to include more examples and additional categories.
- Implement more sophisticated preprocessing techniques to further enhance model performance.
