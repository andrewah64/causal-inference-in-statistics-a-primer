# Why study causation?

- Traditional statistics are able to find associational patterns in data, but are not able to answer questions about causation.
- Causation allows to us to answer interventional and counterfactual questions.
    - Intervention: what if we did X?
    - Counterfactual: what if we had done X?
- Causation allows us to formulate and answer questions about how and why changes to one variable's value causes changes to another.
    - For example, is malaria transmitted by "mal-air", or mosquitos?

# Simpson's paradox

- This is a reference to datasets in which something is true at a population level but not true for every subgroup. One may ask: how can this be true? How can a drug, be harmful for the population as a whole, but helpful for the subgroups of men and women, which when taken together are the entire population. Pearl argues that Simpson's paradox is caused by not considering the causal mechanisms which generated the data.

## Simpson's paradoc: an example

||Drug|No drug|
|Men|81/87|234/270|
|Women|192/263|55/80|
Combined|273/350|289/350|
