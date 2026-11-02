# Movie Review Analysis Using Python and Generative AI

## Project Overview

This project analyzes movie reviews from the Rotten Tomatoes dataset using Natural Language Processing (NLP) and Generative AI.

It uses a pre-trained DistilBERT model for sentiment classification and a BART model for text summarization.

## Development Experience

I developed this project as part of my hands-on learning journey in Data Science and Generative AI.

During development, I worked with Hugging Face datasets and pre-trained Transformer models to understand how NLP can be applied to real-world text analysis.

Some of the concepts I explored include:

- Preparing and transforming unstructured text data.
- Using DistilBERT for sentiment classification.
- Understanding batch inference and execution time.
- Calculating sentiment statistics and visualizing results.
- Using BART for automated text summarization.
- Preparing and saving AI-generated analysis reports.

I also encountered compatibility issues with newer versions of the Transformers library and worked through them to run the summarization pipeline successfully.

## Project Objectives

- Load and prepare movie review data.
- Perform sentiment analysis.
- Calculate sentiment statistics and confidence scores.
- Visualize positive and negative sentiment distribution.
- Generate an AI-powered professional summary.
- Save the final report as a text file.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Jupyter Notebook

## Dataset

**Dataset:** Rotten Tomatoes Movie Reviews

**Hugging Face ID:** `cornell-movie-review-data/rotten_tomatoes`

The project uses a random sample of 1,000 reviews from the training dataset.

## Project Workflow

1. Python environment setup and library installation.
2. Dataset loading using Hugging Face.
3. Data preparation using Pandas.
4. Creation of synthetic attributes.
5. Sentiment classification using DistilBERT.
6. Calculation of sentiment statistics.
7. Sentiment distribution visualization.
8. Selection of representative reviews.
9. Preparation of a structured analysis document.
10. Professional summary generation using BART.
11. Saving the final report.

## Models Used

### DistilBERT

Model: `distilbert-base-uncased-finetuned-sst-2-english`

Used for positive and negative sentiment classification.

### BART

Model: `facebook/bart-large-cnn`

Used for generating a summary from the prepared analysis document.

## Results

| Metric | Result |
|---|---:|
| Total reviews | 1,000 |
| Positive reviews | 516 (52%) |
| Negative reviews | 484 (48%) |
| Average positive confidence | 98.8% |
| Average negative confidence | 98.8% |

*Confidence scores are not the same as model accuracy.*

## Key Concepts Learned

- Natural Language Processing
- Pre-trained Transformer models
- Sentiment analysis
- Batch processing
- Model inference
- Confidence scores
- Data visualization
- Prompt design and iteration
- Text summarization
- Automated report generation
- Python file handling

## Limitations

- Analysis is based on a sample of 1,000 reviews.
- Pre-trained models were used without training them from scratch.
- AI-generated summaries may contain unsupported information.
- Generated reports require human validation.

## Future Improvements

- Add accuracy, precision, recall, and F1-score.
- Implement automated data quality checks.
- Improve factual validation of AI-generated summaries.
- Build an interactive dashboard.
- Refactor the workflow into reusable Python functions.

## Author

**Mrunal Sonekar**

Data Science | Python | Machine Learning | Generative AI
