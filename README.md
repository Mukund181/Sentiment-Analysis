# Mental Health Sentiment Analysis

This project uses a BERT model to analyze the sentiment of mental health related text, like social media posts or statements. It tries to predict whether the sentiment behind a piece of text is positive, neutral, or negative. 

### What's inside:
- `Mental_Health_Analysis.ipynb`: The main jupyter notebook holding all the code. It loads the text data, processes it, and classifies the sentiment using a pre-trained BERT model from hugging face.
- `dataset.txt`: the dataset with the text examples used for the project.

### Tech stack used:
- Transformers (Hugging Face) for the BERT model
- TensorFlow / PyTorch
- Scikit-learn for preprocessing
- Pandas & NumPy for data handling

### How to use
1. Make sure Python and jupyter are set up on your machine.
2. Install the required libraries if you don't have them (`pip install transformers tensorflow torch scikit-learn pandas numpy`).
3. Open `Mental_Health_Analysis.ipynb` and run the cells from top to bottom.
