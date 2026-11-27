# Problem Framing

## Business context
Discount campaigns are useful to attract customers in, but not everyone stays once the discount ends. This project aims to understand the customers who do stay and to analyse how they shopped before and during a campaign, and which behavioural patterns, such as habit, discovery or deal-seeking, set them apart. 

Knowing who stays, and plausibly why, informs two decisions:
- Where should the next campaign budget go?
- How could campaigns be designed for different customer profiles?

## Key question
- Which behaviours before and during a campaign distinguish the customers who keep buying after it ends?

## Definition of done
When this analysis is done, I should be able to say:
- what share of households keep buying after a campaign ends,
- which behaviours before and during the campaign set them apart from those who stop,
- which behavioural explanations, such as habit, discovery or deal-seeking, these patterns are consistent with, and
- what this suggests for where the next campaign budget should go, with one experiment to test the strongest explanation.

## Out of scope
- Overall campaign effectiveness
- Pricing decisions
- New customer acquisition
- Predicting individual customers' future behaviour
  
## Assumptions and known constraints

### Assumptions
- Each household in the dataset is treated as one customer.
- Transactions in the dataset cover a household's shopping at this retailer.
- A household listed as receiving a campaign is assumed to have been exposed to it.
- Buying in a category after a campaign ends, without a discount, is taken as a sign of staying.

### Known constraints
- The data comes from a single US grocery retailer.
- There is no holdout group, so the effect of campaigns cannot be measured directly.
- In Type A campaigns, coupons were selected for each household based on its past purchases, which can bias results for these campaigns.
- Demographic data, including income, is available for only about 800 of the roughly 2,500 households.
- Coupon redemptions are relatively rare (around 2,300 records), so the analysis cannot rely on redemptions alone.
- There is no attitudinal data such as surveys or attitude measures, so loyalty is inferred from behaviour only.


