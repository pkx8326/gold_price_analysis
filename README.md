# When to sell your gold?

### This project aims to find the best days in any given year to make the most profit from gold investment using Python and simple data analysis. The analysis are based on the following assumption and thought process:

Provided that making profit from your gold investment is your new year resolution, and you buy some gold on the first day of the year, this article will show you how to use Python, Pandas and simple Statistics to strategically find the best days within any given year to sell your gold in order to maximize the profit. You can repeat this process year-after-year (at your own risk, of course).
Assumptions:
- You want to make profit from your gold investment
- You buy some gold on the first day of the year (any year)

The following thought process illustrates the journey that will get us to the the conclusion of what day (or days) are best to sell your gold:
Though process:
1. From the historical gold price data, find the price of the first day of each year. The data should be the compilation of as many years as possible.
2. Find the % price difference of each day in that year compared to the price on the first day of the year (first DOY).
3. Group each day together into 365 (or less) groups, for example, January 3rd of every year is one group, and find the average of the calculated % price difference from process #2.
4. Find the day (or days) with the highest or relatively high average % price difference. These are the days you could sell your gold to likely profit from it according to the calculated average % price difference of that day group.

### Read the full article to get the detailed explanation on the analysis steps and codes from the following link: 
