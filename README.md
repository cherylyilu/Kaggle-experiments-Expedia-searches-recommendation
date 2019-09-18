# Kaggle-Expedia-searches-recommendation
An experiment run by Expedia allows us to estimate how effective their recommendation algorithms are. 
In this experiment, Expedia randomly selected some consumers to receive random hotel rankings rather than those based on their recommendation algorithm. Data source from Kaggle: https://www.kaggle.com/c/expedia-personalized-sort
# Results
The original data is obtained from Kaggle.com and consists of a representative sample of 9,917,530 hotels. 
The overall booking rate is 2.79%. The overall click-through-rate is 4.45%.
* Click-through Rate
Difference in click-through rate when receiving randomized ranking hotels vs. receiving Expedia algorithm ranking hotels shows that Expedia’s ranking algorithm increase the propability of click through of customers only for top 4 position, eg. the biggest impact happens at the first hotel which make customers more likely to click and increase the probablity of click to 1.5 times. The impact of improvement by algorithm decrease along position. For position after 4, Expedia’s ranking algorithm even decreases the desire of customers to click.
* Book Rate
Difference in book rate when receiving randomized ranking hotels vs. receiving Expedia algorithm ranking hotels shows that Expedia’s ranking algorithm increase the propability of book for all positions, eg. the biggest impact happens at the first hotel which make customers more likely to book and increase the probablity of book to 10 times. The impacts of improvement by algorithm are significantly big(beyond 5 times increase) for top 22 position, and decrease as position decreases.

In a word, the Expedia’s recommendations really attracts more customers to book. This kind of attraction impact decreases as ranking position decreases. The Expedia’s recommendations attracts more customers to click only for top 4 hotels, after that Expedia’s recommendations make customers less willing to click.
