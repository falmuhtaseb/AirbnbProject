# AirbnbProject
Analyzed Airbnb listings and looked into what impacts price.

## Overview
We are trying to examine what variables affect price of Airbnb listings, specifically if the review score ratings has an effect on price.
There are 2 possible outcomes to our experiment:
- Review score rating affects price (Positive or negative)
- Review score rating does not affect price.
- If the review score rating does not affect the price, the host will set the price based on their best self judgement and feedback is not within their consideration.
Obtained the NY Airbnb listings data from http://insideairbnb.com 

## Data Overview
- The data set has 37k rows and 74 columns
- The data is aggregated by Listing ID 
- Each row represents a different listing
- Each column represents a feature for the listing (ex. Price, review score rating, etc.)

## Data Cleaning and Preperation
Removed redundant columns that are irrelevant to our analysis
- In the columns that are significant to the analysis, we examined null values and dealt with them using:
  - Mode
  - Median
  - Dropped some missing values
- Used IQR exclude price outliers

## Significant Variables
- Price (numeric)
- Review score rating (scale from 1-5)
- Room type (4 unique room types)
- Amenities (2458 unique amenities)
- Neighborhood (5 boroughs)
- Host response time (4 unique response types)

## Results and Recommendations
In order to set an acceptable higher price for a listing hosts should:
1. Hosts should take care of their property and be nice to the guest so they can receive higher review scores rating.
2. Hosts should respond faster to guests and inquiries as well as have a lower acceptance rate. 
3. Hosts can set a lower minimum night limit and make the house instant bookable to attract more guests. 
4. Some amenities like hair-dryers, out-door furniture, coffee maker and BBQ grill can also significantly increase the value of the listing.
