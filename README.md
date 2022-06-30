
# Zipcodes for Millennials: Where You Should Invest in a Home

As some of the youngest millennials begin to turn 30, the prospect of home ownership is becoming more of a priority for investment. According to the Zillow Consumer Housing Trends Report for 2021, 26 percent of homebuyers are between the ages of 30 and 39. The majority of millennials fall within this age range, with even the youngest millennials turning 30 each year.

This project seeks to identify the top five zipcodes for millennials to invest in a home.

# Business Understanding

My clients are first-time homebuyers who are millennials. I know my clients have incomes in the average, middle-of-the-road range and seeking to know what return on their investment may they see in the first two years.

To measure "best" zipcode based on our client profile, I will evaluate long-term (22 years) and short-term (5 years) return on investment and will forecast median home values out two years.

I will provide clients a range of recommendations, from more safe investments (with less variation in forecast) to more risky investments (with more variation in forecast). Further, I'll provide clients a measure error, so that they may make as informed decision as they can.

## Data Understanding

The data used in this time series modeling comes from the [Zillow Research Page](https://www.zillow.com/research/data/) and includes monthly median home values for over 14,000 zipcodes in the United States dating back to 1996.

## Evaluation of "Best" Zipcodes

To narrow down our list of prospective zipcodes, I focus on cumulative ROI (over the 22 years of the full dataset) and the ROI of the most recent five years.

When making predictions using the model, I evaluate its performance using the mean absolute error, so that I can convey to the clients the dollar amount predictions may be off by.

Lastly, I also include the median home value as a data point to consider for investment as homebuyers will having varying levels of cash on hand with which to make their investment.

## Exploratory Data Analysis


# Modeling Description

# Results

# Recommendations

# Future Work

# For More Information

Please review our full analysis in [our Jupyter Notebook](./index.ipynb) or our [presentation](./ppt-time-series-presentation.pdf).

For any additional questions, please contact **Rebecca Frost-Brewer (frostbrewerr@gmail.com)**

# Repository Structure

```
├── README.md                         <- The top-level README for reviewers of this project
├── index.ipynb                       <- Narrative documentation of analysis in Jupyter notebook
├── img
    ├── churn.png
    └── rfb-headshot.png
├── jnb-time-series.pdf    <- PDF of jupyter notebook
├── ppt-time-series-presentation.pdf        <- PDF version of project presentation
├── readme-time-series.pdf <- PDF of github readme
└── zillow_data.csv                       <- Sourced externally
```
