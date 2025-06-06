<h1>Ethereum Cryptocurrency Semi-encoder PyTorch Architecture prediction with Sentiment Analysis</h1>

The Project tries to model future stock prices by applying sentiment analysis based on Valence Aware Dictionary and sEntiment Reasoner algorithm (VADER). 
The data gathered comes from reddit platform from subreddits concentrating on stock trading and filtered for Cryptocurrency mentions. 
It gets cleaned and processed to generate set of daily sentiment values based on average results from diferent posts and reactions of users. 
The values are then represented in continuos and discret form to check for better model fit.

The results are then parsed in form of csv files to the semi-encoder neural network model consisiting of LSTM, Linear and dropout layer.
The training process is conducted with Stochastic Gradient Descent and MSE. The model is trained on 3000 iterations with early stop for optimization purposes.
For hyperparameter optimization the network is tuned using Ray Tune search space for defining the best set values.

<h1>Features</h1>
1. NLP Data processing and sentiment extraction with daily interval.

2. Model training and deployment with PyTorch Library.

<h1>Installation instructions</h1>

1. Download the project as zip in the top right corner or clone it directly via git bash or github on your machine.
2. Open it with your preferred code editor.
3. Open the console, locate the project directory and run the following command to create Conda environment.

```python
conda create --name <your-name>
```

4. Run following command to install necessary packages from requirements.txt.

```python
conda install --file requirements.txt
```
   
6. Run individual blocks for the final results.
