# Why study causation?

- Traditional statistics are able to find associational patterns in data, but are not able to answer questions about causation.
- Causation allows to us to answer interventional and counterfactual questions.
    - Intervention: what if we did X?
    - Counterfactual: what if we had done X?
- Causation allows us to formulate and answer questions about how and why changes to one variable's value causes changes to another.
    - For example, is malaria transmitted by "mal-air", or mosquitos?

# Simpson's paradox

- This is a reference to datasets in which something is true at a population level but not true for every subgroup. One may ask: how can this be true? How can a drug, be harmful for the population as a whole, but helpful for the subgroups of men and women, which when taken together are the entire population. Pearl argues that Simpson's paradox is caused by not considering the causal mechanisms which generated the data.

||Drug|No drug|
|---|---|---|
|Men|81/87 (93%)|234/270 (87%)|
|Women|192/263 (73%)|55/80 (69%)|
Combined|273/350 (78%)|289/350 (83%)|

## Simpson's paradox: an example

- In a drug trial, we observe the rates of recovery shown in the table below. A higher percentage of men and women who took the drug recover, compared to the people who did not take the drug. However, when the data is aggregated we see the opposite: a higher percentage of people who did not take the drug recovered, compared to those who did.
- The data alone can tell us neither why Simpson's paradox has manifested nor how to avoid it. We need to understand the mechanism(s) which caused the data to be generated. There are 2 points to consider: (1) a person randomly drawn from the 'drug' group is more likely to be a woman (2) oestrogen inhibits the rate of recovery from the disease, regardless of if the drug was taken.
- Because the rate of recovery is dependent on trial participants' sex, conclusions should be drawn from data stratified on sex, not aggregated data. Basing conclusions on sex-stratified data allows Simpson's paradox to be avoided, and conclude the drug is beneficial for men and women.


