# Coupon Acceptance Rate Analysis

This repository contains a detailed analysis of the acceptance rates of coupons across various segments using `pandas` and `seaborn` for data manipulation and visualization.

## Packages Used

- [pandas](https://pandas.pydata.org/): A powerful data analysis and manipulation library for Python.
- [seaborn](https://seaborn.pydata.org/): A Python visualization library based on matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.

## Jupyter Notebook

The analysis is documented in a Jupyter notebook titled `prompt.ipynb`. You can open and run the notebook to explore the data analysis and visualization.

To view the notebook, click on the link below:

[prompt.ipynb](prompt.ipynb)

## Analysis Overview

The first half of the analysis focuses people who received coupons to bars while the second half focuses on those who received coupons for coffee houses. 

The coffee house section includes bar charts to visualize the difference in acceptance rate across each feature and then narrows down to look at a few features with heightened acceptance rates amoung people with an occupation of 'Healthcare Practitioners & Technical' 

## Problem

Determine what the driving factors are in acceptance rates for coffee house coupons.

## Findings

There was consistent evidence of customers who already frequent either bars or coffee houses being likely to accept coupons for those businesses.

Notable factors that indicate likelihood to accept a coffee house coupon in particular include:
- Work in Healthcare Practitioners & Technical or Building & Gounds Cleaning & Maintenance roles
- Are below the age of 21
- Are driving around 10 AM
- Are not in the income range of $75k-$87.5k
- Are not far from the Coffee House

I initially believed that there would be a strong connection between acceptance of the coupon in the morning when heading to work, but the data does not appear to indicte that. There is greater likelihood of accepting the coupon when heading to work but not as much as when the recipient has no urgent destination and there is a much greater likelihood of acceptance at mid morning rather than early morning. This information leads me to believe that coffee houses may be used more for a morning break rather than a start of day energizer. 

Among those in Healthcare, there is an interesting dip in acceptance rates in the middle of the age distribution. I hypothesize that the reasons younger and older people go to coffee houses may differ and warrant further investigation. 