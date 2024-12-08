# Drug Reviews Roject

This project is part of the AAI-500 course in the [Applied Artificial Intelligence Program](https://onlinedegrees.sandiego.edu/masters-applied-artificial-intelligence/) at the University of San Diego (USD).

Key objectives:
Sentiment Analysis: The system will classify review text into positive, negative, or neutral sentiment categories, providing insights into patient experiences with each drug.


## Installation

Ensure appropriate Python libraries are installed in your virtual environent, including:

    pandas
    numpy
    scipy
    statsmodels
    sklearn
    nltk
    transformers[torch]
    accelerate
    imblearn

Ensure you have a compatible IDE for reviewing Jupyter Notebook files.

## Team members
    
- Bosky Atlani: [GitHub](https://github.com/boskya)


## DataSet

https://archive.ics.uci.edu/dataset/462/drug+review+dataset+drugs+com

Kallumadi, S. & Grer, F. (2018). Drug Reviews (Drugs.com) [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5SK5S.

## File Structure
drug-reivews.ipynb contains code that does some preliminary EDA and has training and testing using Naive Bayes and Random Forest
drug-reviews-bert-based contains code that uses BERT base and fine tunes it with drug reviews

## Running the code

drug-reviews-bert-based can take a lot of compute and time to run. It is best to run on google colab or other platforms with GPUs. This project was run using L4 GPU on Google colab. It took appropximately 1.5 hour for 3 epochs. 