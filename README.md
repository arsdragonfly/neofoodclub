# Multinomial Logistic Regression NFC model

This is a multinomial logistic regression model for Food Club of Neopets that takes into account per-pirate capability, favorite bonus, allergy penalty, and positional bonus (yes positional bonus is a thing).

## How to use
Install [Anaconda](www.anaconda.com) and run
```bash
anaconda-project prepare
```
to install the necessary dependencies.

To train the model we need to collect and preprocess history data. There's already some history data under `raw_json` but you could download the full data from the r/neopets Discord by using the `!giverounds` command and unzipping it to the `raw_json` folder. Then, run through the `preprocessing.ipynb` notebook to produce the `history.csv`. Finally, run the `final.ipynb` notebook to train the model and generate bets.

## How it works
[PyLogit](https://github.com/timothyb0912/pylogit)
TODO: detailed explanation