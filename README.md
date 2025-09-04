## Overview
A probabilistic Hangman solver that uses n-gram language models (1-gram to 6-gram) and frequency statistics from a large word dictionary to predict the most likely next letter in the game

## Repository Structure
```text
hangman_ngram/
├── words_250000_train.txt   # Training dictionary of English words
├── hangman_ngram.ipynb      # Main notebook for model development & experiments
├── hangman_api_user.ipynb   
├── hangman.pdf
├── requirements.txt        #requirements file                         
└── README.md                    
```

**Setup Python Environment**

* Create virtual environment and activate it
``` bash
python3 -m venv venv
source venv/bin/activate
```
* Install dependencies:
``` bash
pip install -r requirements.txt
```
**Run the notebook**

* Open notebooks/hangman_ngram.ipynb in Jupyter
* Train n-gram models using the dictionary (words_250000_train.txt)
* Run the solver on sample Hangman words to see predictions step by step

**Requirements**

* Create virtual environment and activate it
``` text
numpy
pandas
scikit-learn
tqdm
regex
```
Save this as the requirements file




