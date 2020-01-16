

## Objective:

Suppose we have a bunch of URLs and we want to know their adult-rating
(i.e., is the url P, or G, or X, or R). This task is difficult for computers,
but easy for humans, and this has led to the growth of crowdsourcing: get
a bunch of humans to give ratings to urls, but use automated techniques to
figure out how much to trust each person’s ratings.
The data is from a paper by Ipeirotis et al. This details an experiment run on Amazon’s Mechanical Turk crowdsourcing system. They ask a bunch of raters (called “turks”) to rate several
urls, but they already know the answers (the true categories) for a few urls,
called the “gold set”. The ratings of the turks on the gold set thus allows us
to judge their accuracy.

- This project checks the correctness of the manual ratings for the sites and predicts rating for the sites, which do not have the ratings

## Data:
- gold.txt
- labels.txt

## Analysis:

- Checks the correctness of the data and calculate the odd ratios using correctness of turks 
- Predict overall odds and category for the URLs 
