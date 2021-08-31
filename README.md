# Amazon Vine Analysis: examining bias in paid vine reviews versus unsolicited, unpaid reviews

## Overview
Start-up company Big Market has been tasked with analyzing product data from Amazon for Client SellBy. They are using the Amazon Vine program and want to understand how incentivized reviews from the vine program differ from unsolicited reviews.  Specifically, they want to know whether the Vine program leads to positivity bias.

## Results
- There were 94 Vine reviews and 40,471 Non-Vine reviews
- There were 48 5-star Vine reviews and 15,663 Non-Vine 5-star reviews
- 51% of the Vine reviews were 5-stars and 39% of the Non-Vine reviews were 5-stars


**Table 1:**  Analysis output table.  Vine reviews are labled as "Paid," while Non-Vine Reviews are labeled as "Unpaid."

![Analysis table](resources/analysis_results.png)

## Summary
The results of this analysis should be interpreted carefully, because relative to the number of unsolicited reviews, there are very few view reviews (over 40,000 versus Non-Vine less than 100 Vine reviews, **Table 1**).  However, the present data show that Vine reviewers are more likely to leave favorable reviews (51% of Vine reviews are 5-star rated, while only 39% of Non-Vine reviews were 5-star rated, **Table 1**).  This suggests that Vine members are biased towards leaving more positive reviews, however, see caveat below.  To confirm whether these apparent differences are statistically significant, a two-sample T-test could be used.

Although the data show that Vine reviews re skewed more positively, this is not necessarily due to positively bias in the Vine reviews; it could be due to negativity bias in the unsolicited reviews.  It is well established that consumers are more likely to leave a review on a product or service that they have had a negative experience with than one they had a positive experience with.  Vine reviewers are more likely to leave a review on a product if they liked it than Non-Vine users, because they are incentivized to leave a review.  Vine reviewers do not receive more compensation for leaving a more positive review though, so they have no external motivation to leave a positive review on product they did not like.  Thus, it is possible that the Vine reviews are more indicative of real customer satisfaction than the unsolicited reviews are.  Teasing out the real effect of positivity bias in the Vine data would require a more controlled study.


