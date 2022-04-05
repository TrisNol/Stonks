# Stonks

<img src="./images/stonks-meme.png" width=250>

The objective of this project is to support people in their daily traiding activities, utilizing the power of Machine Learning.

In it´s core the following approaches are employed:
- `NLP` to issue a rise/fall prediction based on the daily news issued for the company
- `Regression` to issue a prediction on the future price (dynamic time window: long or short)
- `LSTM Module` to issue a prediction based on a neural network

As more solutions might be added in the future, the code will be structured to enable a quick integration.

Of course, these modules require a lot of historic data, which will be provided by the Yahoo! Finance API or other products if neccessary. All information will regularly be persisted in a database that also holds the training and test data for re-training the above ML components.