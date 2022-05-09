# Insurance-Case
Statistical analysis on an Insurance company

## Problem Statement 

The Titan Insurance Company has just installed a new incentive payment scheme for its lift policy sales force. It wants to have an early view of the success or failure of the new scheme. Indications are that the sales force is selling more policies but sales always vary in an unpredictable pattern from month to month and it is not clear that the scheme has made a significant difference.

Life Insurance companies typically measure the monthly output of a salesperson as the total sum assured for the policies sold by that person during a month. For example, suppose salesperson X has, in a month, sold seven policies for which the sums assured are £1000, £2500, £3000,£5000, £10000, £35000. X's output for that month is the total of these sums assured, £61,500. Titan's new scheme is that the sales force receive low regular salaries but are paid large bonuses related to their output (i.e. to the total sum assured of policies sold by them). The scheme is expensive for the company but they are looking for the sales to increase more than compensate. The agreement with the sales force is that if the scheme does not at least break even for the company, it will be abandoned after six months.

The scheme has now been in operation for four months. It has settled down after fluctuations in the first two months due to the changeover. To test the effectiveness of the scheme, Titan has taken a random sample of 30 salespeople, measured their output in the penultimate month before the changeover, and then measured it in the fourth month after the changeover (they have deliberately chosen months not too close to the changeover).

I was tasked as a data analyst in the company the following questions:

i) Conduct a hypothesis test to determine whether the new scheme has significantly raised outputs.

ii) What conclusion does the test lead to?

iii) What observations do you have about this result?


First, conducted an Explanatory Data Analysis on the dataset

Second, Created a null and alternative hypothesis

Third, Chose a significant level = 0.05

Fourth, Calculated the p-value using the t-test on related samples.

Lastly, generated an inference based on the p-value.


Powerpoint presentation to stakeholders on observation:

- If we compare the means of the two sample distributions, we see that even though visually it seems as if New scheme has done better, statistically it does not hold.
- The higher mean in the case of the New scheme can also be attributed to the higher variance compared to Old Scheme.
- The variance of the second data set, 579.00, is 38% more than the variance of the first data set, 418.45. (Squaring of the standard deviation values gives us the values of the variance)
- We are unsure of the sampling error present in the data.
- Unpredictable pattern persists even after the bonus scheme directs the management to work on the lift (product portfolio) and to correct the bonus scheme in proportion to revenue generation rather than policy sale.
- The scheme is expensive for the company but they are looking to compensate it by an increase in sales. The agreement with the sales force is that if the scheme does not at least break even for the company, it will be abandoned after six months. So, it's better for the management to wait for another two months.
- There can be a dip in the New Scheme towards end of the cycle, which suggests that the Sales team may have booked all their sales at the earlier part of the period to get their incentives early or may be waiting till the end of quarter (measurement period) to book all their sales at once. Hence aggregation of data for a quarter may provide more clarity on the performance than for a single month.


