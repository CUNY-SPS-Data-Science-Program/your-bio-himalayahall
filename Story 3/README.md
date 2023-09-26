# Assignment

The CDC publishes firearm mortality for each State per 100,000 persons https://www.cdc.gov/nchs/pressroom/sosmap/firearm_mortality/firearm.htm. Each State' firearm control laws can be categorized as very strict to very lax. The purpose of this Story is to answer the question, " Do stricter firearm control laws help reduce firearm mortality?"
For this assignment you will need to:
Access the firearm mortality data from the CDC using an available API (https://open.cdc.gov/apis.html)

Create a 5 point Likert scale categorizing gun control laws from most lax to strictest and assign each state to the most appropriate Likert bin.

Determine wether stricter gun control laws result in reduced gun violence deaths

Present your story using  heat maps

## Data

## Firearm Related Mortality
Firearm related mortality data for each state from the [CDC](https://www.cdc.gov/nchs/pressroom/sosmap/firearm_mortality/firearm.htm). Data was acquired using the [Socrate API](https://dev.socrata.com) and wrangled for this presentation. See DataWrangling.ipynb for details.

## Gun Law Score
[Giffords Gun Law Scorecard](https://giffords.org/lawcenter/resources/scorecard) for each state. Giffords gun law score have the following scale, from strongest gun laws to weakest: \[A+, A, A-, B+, B, B-, C+, C, C-, D+, D, D-, F\]. 

NOriginal Giffords scores have been coerced into a 5-point [Likert scale](https://en.wikipedia.org/wiki/Likert_scale) and a numeric grade was assigned to each letter grade: \[A: 4, B: 3, C: 2, D: 1, F: 0\]. 

