# Will the Customer Accept the Coupon?

## Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

## Overview

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).

## Goal

In this exercise, we are:
1. exploring data, cleansing it where needed and dropping column(s) if needed (a case where most of the entries do not have a value and hence any imputation can potentially skew the analysis.)
2. segmenting data on types of coupons, trying to understand if there are any patterns in drivers accepting coupons a particular type of coupon.
3. combining different criterias (based on column values e.g. age above 25, passanger is kid(s), number of visits to bar) to identify pattern to a specific combination of filters
4. forming a hypothesis on whether there is value in continuing to offer coupons to drivers and will it result in more business for local businesses

## How to contribute to the repo

Please fork the repo and create a pull request from a branch in your fork against main in origin.

## How to run on local

1. Please use some tool like Anaconda Navigator to get Jupyter lab installed along with it.
2. Run Jupyter lab
3. Import the project and run coupons_analysis_visualizations.ipynb file.
