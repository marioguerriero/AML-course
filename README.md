# Algorithmic Machine Learning - EURECOM Course
This repository contains Jupyter Notebooks for the Algorithmic Machine 
Learning Course at [Eurecom](https://eurecom.fr/).

Those notebooks were developed alongside [Sara Giammusso](https://github.com/sgiammy).

## [Recommender System](https://github.com/marioguerriero/AML-course/blob/master/Recommender_System/RecSys.ipynb)


Building a music recommender system
As its name implies, a recommender system is a tool that helps predicting what a user may or may not like among a list of given items. In some sense, you can view this as an alternative to content search, as recommendation engines help users discover products or content that they may not come across otherwise. For example, Facebook suggests friends and pages to users. Youtube recommends videos which users may be interested in. Amazon suggests the products which users may need... Recommendation engines engage users to services, can be seen as a revenue optimization process, and in general help maintaining interest in a service.

In this notebook, we study how to build a simple recommender system: we focus on music recommendations, and we use a simple algorithm to predict which items users might like, that is called ALS, alternating least squares.


## [Monte Carlo Simulation](https://github.com/marioguerriero/AML-course/blob/master/Monte_Carlo_Simulation/MC.ipynb)

Risk analysis is part of every decision we make when faced with uncertainty, ambiguity, and variability. Indeed, even though we have unprecedented access to information, we can't accurately predict the future. In finance, there is a fair amount of uncertainty and risk involved with estimating the future value of financial products, due to the wide variety of potential outcomes. Monte Carlo simulation (also known as the Monte Carlo Method) allows inspecting many possible outcomes of the decision making process, and can be used to assess the impact of risk: this, in turns, allows for better decision-making under uncertainty.

In this notebook we developed an understanding of Monte Carlo Analysis and
we performed a simulation applied to stock price prediction.

## [House Pricing Prediction](https://github.com/marioguerriero/AML-course/blob/master/House_Pricing_Predictions/house-pricing.ipynb)

In this notebook we analysed a regression problem in which we were asked to
predict house prices. After having performed the data transformation techniques
we considered necessary, we built and evaluated several different regressors.

At the end we obtained an RMSE value of 0.11 on the log of the house prices
using a 10-fold cross validation schema.

## [Time Series Analysis](https://github.com/marioguerriero/AML-course/tree/master/TimeSeries)

Every day, more than 80,000 commercial flights take place around the world, operated by hundreds of airlines. For all aircraft take-off weight exceeding 27 tons, a regulatory constraint requires companies to systematically record and analyse all flight data, for the purpose of improving the safety of flights. Flight Data Monitoring strives to detect and prioritize deviations from standards set by the aircraft manufacturers, the authorities of civil aviation in the country, or even companies themselves. Such deviations, called events, are used to populate a database that enables companies to identify and monitor the risks inherent to these operations.

This notebook was designed to let us manipulate real aeronautical data, provided by the Safran Group. It is divided in two parts: the first part deals with the processing of raw data, we were asked to visualize the data, understand what variables require processing and perform the processing for some of these variables. The second part deals with actual data analysis, and covers some interesting problems.
