# Milan and Paris Stock Exchange analysis with COVID-19

The world is being hit with an invisible enemy, COVID-19 has changed our lives for good. We are in a complete lockdown, and we had to make major changes in our lifestyles and businesses, the impacts of the virus is spreading, disrupting everyday life in Milan and everywhere else in the world, cutting shopping, disrupting global supply chains, real estate market and threatening the economy, whatever crisis management responses guides that may have existed weeks ago now seem to be from another time, the situation is forcing everyone to evolve and adapt their strategies and creativity in real-time. 

According to a report issued by McKinsey & Company, more than 40 percent of the global luxury-goods production happens in Italy, and all the Italian factories have temporarily shut down.

Since the stock market has had to deal with some major changes on its own. In this project, we will build a Python script to analyze the impacts of COVID-19 on stock prices regarding the Milan & Paris Stock Exchanges. We will explore the performance of some of the biggest fashion companies on the market to see how good or bad they have stood against the COVID-19 storm. We will take as reference stock prices before the outbreak in Italy and compare it to the same stock prices a few weeks later until April 21st. We will be doing this by conducting different analysis and by computing daily price changes for multiple stocks. After, we will try to explore the relationship between the stock prices and the daily new numbers of coronavirus cases in Italy.

The companies under investigations are:

AEF.MI (Aeffe in the Milan stock exchange)
MONC.MI (Moncler in the Milan stock exchange)
BC.MI (Brunello Cucinelli in the Milan stock exchange)
SFER.MI (Salvatore Ferragamo in the Milan stock exchange)
TOD.MI (Tod's in the Milan stock exchange)
MC.PA (LVMH group in the Paris stock exchange)
CDI.PA (Christian Dior in the Paris stock exchange)
KER.PA (Kering group in the Paris stock exchange)
Note: To review the code and get your hands on the dataset, please visit my profile on github, and if you are interested in exploring more projects, check my first project about Machine Learning, and the second project about the Real Estate Market COVID-19 disruption.

Let's get started and have a look on our dataset. We choose to investigate the Adj. close prices.

Adjusted closing price accurately reflect that stock's value after accounting for any corporate actions. It is considered to be the true price of that stock and is often used when examining historical returns or performing a detailed analysis of historical returns.

Notice that some days might be missing like the first day of the year as yahoo finance sometimes faces network problems.

