# O.S.T.A v2

An improved variant of [OSTA](https://github.com/styg1an0fficial/O.S.T.A/edit/main/README.md) with support for a MySQL server (currently set as a local host) and additional pages for transaction history and portfolio management for each user.

Over Simplified Stock Trading App (OSTA): Uses a Long Term Short Term Recurrent Neural Network trained on decades of stock data to predict the movement of the stock price over the next week or so. Special features include dynamic adaptability to company performance, the ability to retain successful strategies in memory, and feedback connections, allowing it to process entire sequences of data, not just individual data points.

**Make sure to create a SQL server first through the sql file, then update your details at line 18 in main.**
- LSTM RNN model from [keras](https://keras.io/)
- GUI created using [flet](https://flet.dev/)
- Stock data retreived using [yfinance](https://pypi.org/project/yfinance/).
- Data organisation and manipulation was done using [pandas](https://pandas.pydata.org/).
- Graph were drawn using [plotly](https://plotly.com/).
- S&P 500 values and payment option are **dummies** for this version.
- User information is stored after signup.
- Searching and pressing purchase creates new tuples in SQL server.
<br>

![picture](https://github.com/styg1an0fficial/O.S.T.A/assets/113419133/4d17d93d-34cf-4c38-9522-0d178dc8e22f)
![picture](https://github.com/styg1an0fficial/O.S.T.A/assets/113419133/4d17d93d-34cf-4c38-9522-0d178dc8e22f)
![picture](https://github.com/styg1an0fficial/O.S.T.A/assets/113419133/4cc5d6ed-cc5e-4d75-a63f-69e8018ad27f)

<br>
