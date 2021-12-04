# Click [here](https://nicosolv.github.io/implied-volatility/) to see the notebook: https://nicosolv.github.io/implied-volatility/

Application fo the theory seen in an Optiver lecture: Trading options as a market maker given on 2nd Dec 2021.
I wanted to explore this concept further and by visualising it and by writing an algorithms that hedges the option exposure the way it was explained in the lecture.

The analysis consists out of 5 steps:

1. Retrieving and formatting data
2. Calculating implied volatility
3. Visualizing volatility skew and its movements
4. Calculating the hedge to be market neutral
5. Visualizing the position taking for hedging

Note: This research was done on the QuantConnect platform because of the platform provides of high-resolution data. 
Therefore if you want to run the code, you will have to create an account for yourself and copy-paste the in a notebook on the platform.
