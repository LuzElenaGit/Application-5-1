# Summary of Findings:

This analysis explored coupon acceptance patterns within a driver dataset, revealing several key insights:

- Data Cleaning and Preparation:

- The 'Car' column, exhibiting 99.15% missing data, was removed. Remaining columns with minor missing data (less than 2%) were imputed using the most frequent value.
- Coupon acceptance was determined by filtering records where the 'Y' column equaled 1, resulting in an overall acceptance rate of 56.84%.

- Coupon Acceptance Trends:

Coupon preferences were visualized, indicating a strong preference for Coffee House and Cheap Restaurant (<$20) coupons, followed by Carry Out & Take Away. Bar and expensive Restaurant ($20-$50) coupons were the least favored.

Coupon acceptance demonstrated a positive correlation with temperature, with higher acceptance rates observed during warmer temperatures.

# Bar Coupon Analysis:

Focusing specifically on bar coupons (excluding those who "never" visited), the acceptance rate was 34.59%.

Among those who used bar coupons, 79.79% visited a bar three or fewer times per month, while 20.21% visited more than three times.

Analysis of bar visit frequency, segmented by age (over and under 25), revealed a consistent trend: the majority of both age groups visited bars 1-3 times per month, with fewer visits in the 4-8 and >8 ranges. A significant number of both groups also reported less than one visit.

A subplot comparing the age groups confirmed the correlation in visit frequency.

Drivers meeting specific criteria (bar visits >1/month, no kids, non-farming/fishing/forestry occupations) had a 52.48% coupon acceptance rate.

Specific populations acceptance rates were determined. 
- Drivers that go to bars more than once a month, had passengers that were not kids and were not widowed: 52.48%. 
- Drivers that went to the bar more than once a month and are under 30: 32.52%. 
- Drivers that go to cheap restaurants more than 4 times a month and income is less than 50K: 19.05%.
The frequency of bar coupon usage was heavily skewed towards three or fewer visits per month.

# Independent Investigation

- Analysis of the 'income' column revealed that the acceptance rate of Coffee House coupons by drivers who visited at least once a month was:
27.84% for drivers under 30 years old.
26.07% for drivers over 30 years old.

- When comparing income levels, the acceptance rate for drivers making less than $50K was 29.04%, slightly higher than the 27.84% acceptance rate for drivers making over $50K.

- Furthermore, 11.60% of drivers with incomes over $50K never accepted a Coffee House coupon.
