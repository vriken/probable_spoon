This is a trading script that I've written. To be able to run this, you need to change the paths, and get your avanza username, password, totp secret and account id.

You then run realtime.py, trading.py and avanza_api.py. And the script will start buying and selling stocks based on the channels defined in the best_tickers.

If you want to update the channels, run the optimization_favorites.py, which uses bayesian optimization to find the best channels (currenty broken because of implement_strategy)
