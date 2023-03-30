# Algo_trading Homework

Choose the set of parameters that best improved the trading algorithm returns. To show this work, save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file. (2 points)


Based on the PNG, if we look at the y-axis we can conclude based on the if > actual return buy and if < than actual return, sell algo, the 5 short and 100 long MA window was the best. 

I would probably recommend not using this strategy as it lacks intuition. A more realistic signal is a cross over strategy which is an indication of shorter-term sentiment shift and price momentum (e.g. short signal > long signal, you buy). AS you can see in that PNG, we actaully see an outperformance of it over the "actual returns".

AS for the ML model, the one with the highest accuracy as seen at the very bottom of the notebook is "Support vector machine" with an accuracy score of 56, which isn't very good anyways.