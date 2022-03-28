# CS482-Group4
Group 4's project on House Prices and advanced regression techniques

What is the problem that you will be investigating? Why is it interesting?

With the drastic increase in development of data and machine learning, there has been a proportionate increase in using such tools to derive models for the purpose of prediction in a multitude of fields.  Among these, the housing market remains a staple of the world economy, utilized by both homeowners and entrepreneurs.  By creating a price prediction regression model, anyone would be able to derive a value for a home given the corresponding dataset and use it in assistance in buying and selling homes.  There would also be more transparency as to what goes into a particular home's value, and the specific data that makes one home more valuable than another.  The problem we are investigating is how one can derive a house's value from the most influential data about the house.

This is an interesting problem to solve because of the drastic increase in housing prices that occurs on a year by year basis, and would allow people to further understand the data behind a valuable home.  We are also interested in this because it would allow us to build a tool that can devise if a house is overpriced, underpriced, or at a fair value, which would be an immensely useful tool for home buyers and sellers.


What reading will you examine to provide context and background?
Several established scientific publications on the issue will be presented to provide background of the study.
What data will you use? If you are collecting new data, how will you do it?
The data we will use comes directly from the Kaggle website, giving us access to 79 unique variables that all impact the value of a home.  Examples of such data include, overall condition on a scale of 1-10, roof style, type of foundation, and many more.

What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? You don’t have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on.
Due to the nature of the data, we will be using a regression model algorithm.  Our goal is to derive the value of a particular home given the dataset and determine approximately what that home should be worth. As long as we can make comparisons between the data of a given home and other similar homes, a regression model should be able to derive an objective fair value for a home.

How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?
We will evaluate our result by validating whether or not our result will show the correct price of the houses. We expect to show plots and figures that show the sales prices recognized visually when the data is plotted in scatter plot form. These scatter plots can show the different houses in comparison to their sale prices. We plan to apply logistic regression to determine the sale prices of the houses. It will enable us to create prediction algorithms which will gather present data by comparing these to existing data patterns to authenticate our results. As a result, the value of the SalePrice variable will be displayed.
