# Sentiment-Analysis-of-Amazon-Reviews-Using-Python-and-NLTK


# Sentiment Analysis in Python

This repository contains a Jupyter Notebook for performing sentiment analysis using Python. The notebook is part of a tutorial available on my [YouTube channel](https://www.youtube.com/channel/UCxladMszXan-jfgzyeIMyvw).

## Project Overview

In this project, we use two different techniques for sentiment analysis:
1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)** - A lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media.
2. **RoBERTa Pretrained Model** from Huggingface - A robustly optimized BERT approach, which is a state-of-the-art NLP model.

## Dataset

The dataset used in this project is the Amazon Fine Food Reviews dataset. For the purposes of this tutorial, we are using a subset of 500 reviews from this dataset.

## Steps in the Notebook

1. **Reading in Data and NLTK Basics:**
    - Load the dataset.
    - Basic data exploration.

2. **VADER Sentiment Analysis:**
    - Installation and setup of VADER.
    - Applying VADER for sentiment analysis.
    
3. **RoBERTa Sentiment Analysis:**
    - Installation and setup of Huggingface's transformers library.
    - Applying the pre-trained RoBERTa model for sentiment analysis using the Huggingface pipeline.

## Requirements

To run the notebook, you need to have the following libraries installed:

\`\`\`bash
pip install pandas numpy matplotlib seaborn nltk transformers
\`\`\`

## Usage

1. Clone the repository:

\`\`\`bash
git clone https://github.com/your-username/sentiment-analysis-python-youtube-tutorial.git
\`\`\`

2. Navigate to the project directory:

\`\`\`bash
cd sentiment-analysis-python-youtube-tutorial
\`\`\`

3. Install the required libraries:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

4. Open the Jupyter Notebook:

\`\`\`bash
jupyter notebook sentiment-analysis-python-youtube-tutorial.ipynb
\`\`\`

5. Follow the steps in the notebook to perform sentiment analysis.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the \`LICENSE\` file for details.

## Acknowledgments

- The VADER sentiment analysis tool.
- Huggingface for providing the pre-trained RoBERTa model.
- The creators of the Amazon Fine Food Reviews dataset.
- Inspiration from various tutorials and resources available online.

## Contact

If you have any questions or suggestions, feel free to contact me through my [YouTube channel](https://www.youtube.com/channel/UCxladMszXan-jfgzyeIMyvw).
