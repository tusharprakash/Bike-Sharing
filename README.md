# Problem Statement:

### 
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.
###
# Business Goal:

###
It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
###

# Objective:

###
Build a multi-variate regression model to predict the demand of bike rentals on any given day, given the various attributes of the day and the user. Perform EDA, report the significant variables, build the final using model using those, and check that the assumptions of linear regression are being satisfued by analyzing the residuals. Take care to ensure that the final model is sufficiently generalized and does not overfit the training data.
###

# Conclusions:

###
R-Squared of 0.805 is obtained, which is decent and not significantly lower than the training data. This means that *80.05% of variation in count is being explained by the variables selected* in the model. It is oberved that the scatter plot of actual vs. predicted counts falls neatly on a 45 degree line, though a slight upward bias can be seen suggesting that relationship of count of rentals and the underlying variables is almost, but not exactly linear. 

The distplot of error terms show that they are more or less normally distributed, suggesting that they are independent and identically distributed. The Q-Q plots of residuals show fatter tails than normal distribution, but thinner than T-distribution. This suggestes that the *model is valid and usable*, and the assumptions of linear regression are being met.
###







